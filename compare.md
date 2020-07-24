---
layout: default
title: Features
nav_order: 4
last_modified_date: 2019-04-18T11:21:35
---

# SWIG Features

This information is based on the SWIG-4.0.0 release.

### Code Generation

SWIG currently generates wrapper code for the following different target
languages:

-   C\#
-   D
-   Go
-   Guile
-   Java
-   Javascript
-   Lua
-   MzScheme/Racket
-   OCaml
-   Octave
-   Perl
-   PHP
-   Python
-   R
-   Ruby
-   Scilab
-   Tcl

In addition to this, the parse tree can be exported as XML.

### ISO C

SWIG is capable of wrapping all of ISO C99. Features include:

-   Handling of *all* ISO C datatypes.
-   Global functions, global variables, and constants.
-   Structures and unions.
-   Pointers.
-   Arrays and multidimensional arrays.
-   Pointers to functions.
-   Variable length arguments.
-   Typedef.
-   Callbacks.
-   Enums.

### ISO C++

SWIG provides wrapping support for ISO C++98 to C++17.

-   All C++ datatypes.
-   References.
-   Pointers to members.
-   Classes.
-   Inheritance and multiple inheritance.
-   Overloaded functions and methods (using dynamic dispatch).
-   Overloaded operators.
-   Static members.
-   Namespaces (including using declarations, aliases, nesting, etc.)
-   Templates
-   Nested classes
-   Member templates
-   Template specialization and partial specialization.
-   Smart pointers
-   C++ library support for strings and the STL.
-   The majority of the newer C++11 to C++17 standard features.

C++ users who rely on advanced template programming techniques (e.g.,
template meta-programming) should also be aware that SWIG currently
requires manual instantiation of all template classes. Therefore, if
your application somehow involves the instantiation of 50000 template
classes, your mileage might vary.

### Preprocessing

SWIG provides a full C preprocessor with the following features:

-   Macro expansion.
-   Automatic wrapping of \#define statements as constants (when
    applicable).
-   Support for C99 (variadic macro expansion).

### Doxygen documentation

Doxygen documentation comments in C++ comments are parsed and converted
into equivalent Java and Python documentation comments.

### Customization features

SWIG provides control over most aspects of wrapper generation. Most of
these customization options are fully integrated into the C++ type
system\--making it easy to apply customizations across inheritance
hierarchies, template instantiations, and more. Features include:

-   Customized type conversion/marshaling.
-   Exception handling.
-   Class/structure extension.
-   Memory management.
-   Ambiguity resolution.
-   Template instantiation.
-   File import and cross-module linking.
-   Code inclusion, helper function support.
-   Extensive diagnostics (error/warning messages including fine grained
    warning suppression).
-   Extended SWIG macro handling.

------------------------------------------------------------------------

Feedback and questions concerning this site should be posted to the
[swig-devel](mail.html) mailing list.

Last modified : Tue Apr 16 19:06:49 2019
