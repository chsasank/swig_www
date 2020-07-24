---
layout: default
title: Compatibility
nav_order: 3
last_modified_date: 2019-04-18T11:21:35
---

# Compatibility

SWIG is known to work on the following platforms :

-   Unix

    > SWIG is configured and built using an autoconf script so it is
    > relatively easy to install on almost any flavor of Unix. However,
    > most of SWIG\'s development takes place under Linux. While the
    > configuration script tries to determine the proper settings for
    > your machine, some tweaking may be required to compile the
    > examples included in the distribution (especially if you are using
    > a version of Unix such as AIX or HPUX).

-   Microsoft Windows

    > SWIG works on 32-bit and 64-bit versions of Windows. You may also
    > need to determine which compiler has been used to compile the
    > various scripting languages that you will be using. In general,
    > compiling the SWIG generated code with a different C++ compiler
    > than the one that was used to compile the target scripting
    > language may not work (for example, trying to create a Tcl/Tk
    > module using the Borland compiler when Tcl/Tk has been compiled
    > with Visual C++).

-   Macintosh

    > swig-1.3.12 and later support OS-X/Darwin. Simply download the
    > Unix sources, configure, and build from the command terminal.

### []{#SupportedLanguages} Supported Languages

The following scripting languages were supported in the final SWIG 1.1
release.

-   Tcl 8.0 and newer versions.
-   Python 1.5 and newer.
-   Perl 5.003 or newer.
-   Guile 1.3.4 and newer.

The following languages are also supported in swig-1.3.6 onwards.

-   Java JDK 1.1 and newer.
-   Ruby.
-   Mzscheme.

* PHP support was added in swig-1.3.11.
* Objective Caml (OCaml) and Pike support was added in swig-1.3.14.
* Support for C\# and the Chicken scheme compiler was added in
* swig-1.3.18.
* Support for Allegro CL and Modula-3 was added in swig-1.3.22.
* Support for Lua, CLISP and Common Lisp with UFFI was added in
* swig-1.3.26.
* Support for Common Lisp with CFFI was added in swig-1.3.28.
* Support for R was added in swig-1.3.30.
* Support for Octave was added in swig-1.3.35.
* Support for the Go language was added in swig-2.0.1.
* Support for D was added in swig-2.0.2.
* Support for Javascript was added in swig-3.0.1.
* Support for Scilab was added in swig-3.0.5.
* Support for Allegrocl, CFFI, Chicken, CLISP, Modula3, S-EXP, UFFI and
* Pike was removed in swig-4.0.0.

Any newer versions of these languages should be assumed to be supported
unless otherwise indicated.

### Compilation Requirements

SWIG is implemented in C and C++ and is distributed in source form. You
will need a working C++ compiler (e.g. g++) to build SWIG and at least
one of the supported scripting languages to use it (or else it isn\'t
going to be very useful). SWIG does not depend upon any of the supported
scripting languages for its own compilation. Finally, although SWIG is
partly written in C++, a C++ compiler is not required to use SWIG\--it
works just fine with both ISO C and C++.

------------------------------------------------------------------------

Feedback and questions concerning this site should be posted to the
[swig-devel](mail.html) mailing list.

Last modified : Tue Apr 16 19:43:02 2019
