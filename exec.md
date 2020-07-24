# What is Swig - Executive Summary

SWIG is an interface compiler that connects programs written in C and
C++ with scripting languages such as Perl, Python, Ruby, and Tcl. It
works by taking the declarations found in C/C++ header files and using
them to generate the wrapper code that scripting languages need to
access the underlying C/C++ code. In addition, SWIG provides a variety
of customization features that let you tailor the wrapping process to
suit your application.

John Ousterhout (creator of Tcl) has written a
[paper](https://www.tcl.tk/doc/scripting.html) that describes the
benefits of scripting languages. SWIG makes it fairly easy to connect
scripting languages with C/C++ code.

SWIG is used in a number of ways:

-   **Building more powerful C/C++ programs**. Using SWIG, you can
    replace the main() function of a C program with a scripting
    interpreter from which you can control the application. This adds
    quite a lot of flexibility and makes the program \"programmable.\"
    That is, the scripting interface allows users and developers to
    easily modify the behavior of the program without having to modify
    low-level C/C++ code. The benefits of this are numerous. In fact
    think of all of the large software packages that you use every
    day\-\--nearly all of them include special a macro language,
    configuration language, or even a scripting engine that allows users
    to make customizations.

-   **Rapid prototyping and debugging**. SWIG allows C/C++ programs to
    be placed in a scripting environment that can be used for testing
    and debugging. For example, you might test a library with a
    collection of scripts or use the scripting interpreter as an
    interactive debugger. Since SWIG requires no modifications to the
    underlying C/C++ code, it can be used even if the final product does
    not rely upon scripting.

-   **Systems integration**. Scripting languages work fairly well for
    controlling and gluing loosely-coupled software components together.
    With SWIG, different C/C++ programs can be turned into scripting
    language extension modules. These modules can then be combined
    together to create new and interesting applications.

-   **Construction of scripting language extension modules**. SWIG can
    be used to turn common C/C++ libraries into components for use in
    popular scripting languages. Of course, you will still want to make
    sure that no-one else has already created a module before doing
    this.

SWIG is sometimes compared to interface definition language (IDL)
compilers such as those you find with systems such as CORBA and COM.
Although there are a few similarities, the whole point of SWIG is to
make it so you don\'t have to add an extra layer of IDL specifications
to your application. If anything, it\'s much more of a rapid application
development and prototyping tool. Specifically:

-   **ISO C/C++ syntax**. SWIG parses ISO C++ that has been extended
    with a number of special directives. As a result, interfaces are
    usually built by grabbing a header file and tweaking it a little
    bit. This particular approach is especially useful when the
    underlying C/C++ program undergoes frequent modification.

-   **SWIG is not a stub generator**. SWIG produces code that you simply
    compile and run. You don\'t have to fill in any stubs or write
    special client/server code as you do with RPC-like systems.

-   **SWIG does not define a protocol nor is it a component framework.**
    SWIG does not define mechanisms or enforce rules regarding the way
    in which software components are supposed to interact with each
    other. Nor is it a specialized runtime library or alternative
    scripting language API. SWIG is merely a code generator that
    provides the glue necessary to hook C/C++ to other languages.

-   **Designed to work with existing C/C++ code**. SWIG requires little,
    if any, modifications to existing code. For the most part, it
    encourages you to keep a clean separation between C/C++ and its
    scripting interface.

-   **Extensibility**. SWIG provides a variety of customization options
    that allow you to blow your whole leg off if that\'s what you want
    to do. SWIG is not here to enforce programming morality.

Finally, it is worth noting that even though SWIG is occasionally
compared to other more specialized scripting language extension building
tools (e.g., Perl XS, Python bgen, etc.), its primary audience is C/C++
programmers who want to add a scripting language component to their
applications. Because of this, SWIG tends to have a slightly different
focus than tools designed to build small modules for widespread use in a
scripting language distribution. applications.

A number of [papers and tutorials](doc.html) describing SWIG are
available. You can also view a simple [tutorial](tutorial.html) to see
an example of SWIG in action, or check out how other people are using
SWIG in their [projects](projects.html).

SWIG has been freely available in various forms since February, 1996 and
a large number of developers have made contributions. Today, SWIG
remains an all-volunteer effort. Approximately 875 people subscribe to
the [swig](mail.html) mailing list and a public Git repository is
available at [Github](https://github.com/swig/swig). Versions of SWIG
can now be found in most Linux distributions (however, you\'ll almost
certainly want to get the latest version here).

------------------------------------------------------------------------

Feedback and questions concerning this site should be posted to the
[swig-devel](mail.html) mailing list.

Last modified : Thu Apr 18 20:05:49 2019
