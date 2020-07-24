---
layout: default
title: Tutorial
nav_order: 5
last_modified_date: 2019-04-18T20:11:49
---

# Tutorial

So you want to get going in a hurry? To illustrate the use of SWIG,
suppose you have some C functions you want added to Tcl, Perl, Python,
Java and C\#. Specifically, let's say you have them in a file
`example.c`

```c
/* File : example.c */
#include <time.h>
double My_variable = 3.0;

int fact(int n) {
    if (n <= 1) return 1;
    else return n*fact(n-1);
}

int my_mod(int x, int y) {
    return (x%y);
}
    
char *get_time()
{
    time_t ltime;
    time(&ltime);
    return ctime(&ltime);
}
```
   

### Interface file

Now, in order to add these files to your favorite language, you need to
write an \"interface file\" which is the input to SWIG. An interface
file for these C functions might look like this :

```
/* example.i */
%module example
%{
/* Put header files here or function declarations like below */
extern double My_variable;
extern int fact(int n);
extern int my_mod(int x, int y);
extern char *get_time();
%}

extern double My_variable;
extern int fact(int n);
extern int my_mod(int x, int y);
extern char *get_time();
```

### Building a Tcl module

At the UNIX prompt, type the following (shown for Linux, see the [SWIG
Wiki Shared Libraries
FAQ](https://github.com/swig/swig/wiki/FAQ#shared-libraries) page for
help with other operating systems):

```bash
$ swig -tcl example.i
$ gcc -fpic -c example.c example_wrap.c -I/usr/local/include 
$ gcc -shared example.o example_wrap.o -o example.so
$ tclsh
% load ./example.so example
% puts $My_variable
3.0
% fact 5
120
% my_mod 7 3
1
% get_time
Sun Feb 11 23:01:07 2018
% 
```

The `swig` command produces a file
[`example_wrap.c`](tutorial/example_wrap.html) that should be compiled
and linked with the rest of the program. In this case, we have built a
dynamically loadable extension that can be loaded into the Tcl
interpreter using the `load` command.

### Building a Python module

Turning C code into a Python module is also easy. Simply do the
following (shown for Irix, see the [SWIG Wiki Shared Libraries
FAQ](https://github.com/swig/swig/wiki/FAQ#shared-libraries) page for
help with other operating systems):

```bash
$ swig -python example.i
$ gcc -c example.c example_wrap.c -I/usr/local/include/python2.7
$ ld -shared example.o example_wrap.o -o _example.so 
```   

We can now use the Python module as follows :

```python
>>> import example
>>> example.fact(5)
120
>>> example.my_mod(7,3)
1
>>> example.get_time()
'Sun Feb 11 23:01:07 2018'
>>>
```     

### Building a Perl module

You can also build a Perl5 module as follows (shown for Linux, see the
[SWIG Wiki Shared Libraries
FAQ](https://github.com/swig/swig/wiki/FAQ#shared-libraries) page for
help with other operating systems):

```bash
$ swig -perl5 example.i
$ gcc -c `perl -MConfig -e 'print join(" ", @Config{qw(ccflags optimize cccdlflags)}, \
     "-I$Config{archlib}/CORE")'` example.c example_wrap.c
$ gcc `perl -MConfig -e 'print $Config{lddlflags}'` example.o example_wrap.o -o example.so
$ perl
use example;
print $example::My_variable,"\n";
print example::fact(5),"\n";
print example::get_time(),"\n";
<ctrl-d>
3.0
120
Sun Feb 11 23:01:07 2018
$ 
```


### Building a Java module

SWIG will also generate JNI code for accessing C/C++ code from Java.
Here is an example building a Java module (shown for Cygwin, see the
[SWIG Wiki Shared Libraries
FAQ](https://github.com/swig/swig/wiki/FAQ#shared-libraries) page for
help with other operating systems):

```bash
$ swig -java example.i
$ gcc -c example.c example_wrap.c -I/c/jdk1.3.1/include -I/c/jdk1.3.1/include/win32
$ gcc -shared example.o  example_wrap.o -mno-cygwin -Wl,--add-stdcall-alias  -o example.dll
$ cat main.java
public class main {
  public static void main(String argv[]) {
    System.loadLibrary("example");
    System.out.println(example.getMy_variable());
    System.out.println(example.fact(5));
    System.out.println(example.get_time());
  }
}
$ javac main.java
$ java main
3.0
120
Mon Mar  4 18:20:31  2002
$
```

### Building a C\# module

SWIG will also generate code for accessing C/C++ code from C\# using
PInvoke. Here is an example building a C\# module (shown for Linux, see
the [SWIG Wiki Shared Libraries
FAQ](https://github.com/swig/swig/wiki/FAQ#shared-libraries) page for
help with other operating systems). It uses the open source
[Mono](http://www.mono-project.com/) C\# compiler which runs on Windows
and most Unix systems, but the Microsoft C\# compiler (csc.exe) works
equally well on Windows:

```bash
$ swig -csharp example.i
$ gcc -c -fpic example.c example_wrap.c
$ gcc -shared example.o  example_wrap.o   -o libexample.so
$ mono-csc -out:runme.exe *.cs
$ cat runme.cs
using System;
public class runme {
    static void Main() {
        Console.WriteLine(example.My_variable);
        Console.WriteLine(example.fact(5));
        Console.WriteLine(example.get_time());
    }
}
$ ./runme.exe
3
120
Thu Nov 17 21:24:13 2016

$
```

### SWIG for the truly lazy

As it turns out, it is not always necessary to write a special interface
file. If you have a header file, you can often just include it directly
in the SWIG interface. For example:

```
%module example
%{
/* Includes the header in the wrapper code */
#include "header.h"
%}

/* Parse the header file to generate wrappers */
%include "header.h"
```

Alternatively, some people might just include SWIG directives in a
header file with conditional compilation. For example:

```
#ifdef SWIG
%module example
%{
#include "header.h"
%}
#endif

extern int fact(int n);
...
```

### Running SWIG under Microsoft Windows

SWIG also works perfectly well under all known 32-bit and 64-bit
versions of Windows. SWIG is typically invoked from the command prompt
and can be used with NMAKE or as custom builds from Visual Studio.
Modules are typically compiled in the form of a DLL that can be
dynamically loaded into Java, Python, or whatever language you are
using.

### That's it (well, more or less)

That's about everything you need to know to get started. Here's the
short checklist :

-   Make sure you specify a module name.
-   Use ISO C/C++ syntax
-   Figure out how to compile a shared library module / dynamic link
    library (may require reading a few man pages for your compiler).
-   Relax.

### Surely there's more to it...

The above example is intentionally simple, but the general idea extends
to more complicated C/C++ programming tasks. In fact, it is important to
know that SWIG is a fairly complete C++ compiler with support for nearly
every language feature. This includes preprocessing, pointers, classes,
inheritance, and even C++ templates. SWIG can also be used to package
structures and classes into proxy classes in the target
language\-\--exposing the underlying functionality in a very natural
manner.

To illustrate, suppose you wanted to wrap the following C++ data
structure:

```cpp
// pair.h.  A pair like the STL
namespace std {
   template<class T1, class T2> struct pair {
       T1 first;
       T2 second;
       pair() : first(T1()), second(T2()) { };
       pair(const T1 &f, const T2 &s) : first(f), second(s) { }
   };
}
```

To wrap with SWIG, you might specify the following interface:

```
// pair.i - SWIG interface
%module pair
%{
#include "pair.h"
%}

// Ignore the default constructor
%ignore std::pair::pair();      

// Parse the original header file
%include "pair.h"

// Instantiate some templates

%template(pairii) std::pair<int,int>;
%template(pairdi) std::pair<double,int>;
```

Now, compiling for Linux (Python):

```bash
$ swig -python -c++ pair.i
$ g++ -c -fpic pair_wrap.c -I/usr/include/python2.7
$ g++ -shared pair_wrap.o -o _pair.so
$ python
Python 2.7.15 (default, Nov 12 2018, 14:31:15) 
[GCC 7.3.0] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> import pair
>>> a = pair.pairii(3,4)
>>> a.first
3
>>> a.second
4
>>> a.second = 16
>>> a.second
16
>>> b = pair.pairdi(3.5,8)
>>> b.first
3.5
>>> b.second
8
```
