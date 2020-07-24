Welcome to SWIG
---------------

SWIG is a software development tool that connects programs written in C
and C++ with a variety of high-level programming languages. SWIG is used
with different types of target languages including common scripting
languages such as Javascript, Perl, PHP, Python, Tcl and Ruby. The list
of [supported languages](compat.html#SupportedLanguages) also includes
non-scripting languages such as C\#, D, Go language, Java including
Android, Lua, OCaml, Octave, Scilab and R. Also several interpreted and
compiled Scheme implementations (Guile, MzScheme/Racket) are supported.
SWIG is most commonly used to create high-level interpreted or compiled
programming environments, user interfaces, and as a tool for testing and
prototyping C/C++ software. SWIG is typically used to parse C/C++
interfaces and generate the \'glue code\' required for the above target
languages to call into the C/C++ code. SWIG can also export its parse
tree in the form of XML. SWIG is free software and the code that SWIG
generates is compatible with both commercial and non-commercial
projects.

-   [Download](survey.html) the latest version.
-   [Documentation, papers, and presentations](doc.html)
-   [Features](compare.html).
-   [Mailing Lists](mail.html)
-   [Bug tracking](bugs.html)
-   [SwigWiki!](https://github.com/swig/swig/wiki)

### Recent News

**2020/06/08** - [SWIG-4.0.2 released](https://sourceforge.net/p/swig/news/2020/06/swig-402-released/)

:   ::: {.markdown_content}
    **SWIG-4.0.2 summary:**

    -   A few fixes around doxygen comment handling.
    -   Ruby 2.7 support added.
    -   Various minor improvements to C\#, D, Java, OCaml, Octave,
        Python, R, Ruby.
    -   Considerable performance improvement running SWIG on large
        interface files.
    :::

**2019/08/21** - [SWIG-4.0.1 released](https://sourceforge.net/p/swig/news/2019/08/swig-401-released/)

:   ::: {.markdown_content}
    SWIG-4.0.1 summary:

    -   SWIG now cleans up on error by removing all generated files.
    -   Add Python 3.8 support.
    -   Python Sphinx compatibility added for Doxygen comments.
    -   Some minor regressions introduced in 4.0.0 were fixed.
    -   Fix some C++17 compatibility problems in Python and Ruby
        generated code.
    -   Minor improvements/fixes for C\#, Java, Javascript, Lua,
        MzScheme, Ocaml, Octave and Python.
    :::

**2019/04/28** - [SWIG-4.0.0 released](https://sourceforge.net/p/swig/news/2019/04/swig-400-released/)

:   ::: {.markdown_content}
    SWIG-4.0.0 summary

    -   Support for Doxygen documentation comments which are parsed and
        converted into JavaDoc or PyDoc comments.
    -   STL wrappers improved for C\#, Java and Ruby.
    -   C++11 STL containers added for Java, Python and Ruby.
    -   Improved support for parsing C++11 and C++14 code.
    -   Various fixes for shared_ptr.
    -   Various C preprocessor corner case fixes.
    -   Corner case fixes for member function pointers.
    -   Python module overhaul by simplifying the generated code and
        turning most optimizations on by default.
    -   %template improvements wrt scoping to align with C++ explicit
        template instantiations.
    -   Added support for a command-line options file (sometimes called
        a response file).
    -   Numerous enhancements and fixes for all supported target
        languages.
    -   SWIG now classifies the status of target languages into either
        \'Experimental\' or \'Supported\' to indicate the expected
        maturity level.
    -   Support for CFFI, Allegrocl, Chicken, CLISP, S-EXP, UFFI, Pike,
        Modula3 has been removed.
    -   Octave 4.4-5.1 support added.
    -   PHP5 support removed, PHP7 is now the supported PHP version.
    -   Minimum Python version required is now 2.7, 3.2-3.7 are the only
        other versions supported.
    -   Added support for Javascript NodeJS versions 2-10.
    -   OCaml support is much improved and updated, minimum OCaml
        version required is now 3.12.0.
    :::

**2017/01/28** - [SWIG-3.0.12 released](https://sourceforge.net/p/swig/news/2017/01/swig-3012-released/)

:   ::: {.markdown_content}
    SWIG-3.0.12 summary:

    -   Add support for Octave-4.2.
    -   Enhance %extend to support template functions.
    -   Language specific enhancements and fixes for C\#, D, Guile,
        Java, PHP7.
    :::

**2016/12/29** - [SWIG-3.0.11 released](https://sourceforge.net/p/swig/news/2016/12/swig-3011-released/)

:   ::: {.markdown_content}
    SWIG-3.0.11 summary:\
    - PHP 7 support added.\
    - C++11 alias templates and type aliasing support added.\
    - Minor fixes and enhancements for C\# Go Guile Java Javascript
    Octave PHP Python R Ruby Scilab XML.
    :::

**2016/06/12** - [SWIG-3.0.10 released](https://sourceforge.net/p/swig/news/2016/06/swig-3010-released/)

:   ::: {.markdown_content}
    This release fixes a couple of important regressions in SWIG-3.0.9
    for smart pointers and importing Python modules.
    :::

**2016/05/29** - [SWIG-3.0.9 released](https://sourceforge.net/p/swig/news/2016/05/swig-309-released/)

:   ::: {.markdown_content}
    Summary of changes in SWIG-3.0.9

    -   Add support for Python\'s implicit namespace packages.
    -   Fixes to support Go 1.6.
    -   C++11 std::array support added for Java.
    -   Improved C++ multiple inheritance support for Java/C\# wrappers.
    -   Various other minor fixes and improvements for C\#, D, Go, Java,
        Javascript, Lua, Python, R, Ruby, Scilab.
    :::

**2015/12/31** - [SWIG-3.0.8 released](https://sourceforge.net/p/swig/news/2015/12/swig-308-released/)

:   ::: {.markdown_content}
    SWIG-3.0.8 summary:\
    - pdf documentation enhancements.\
    - Various Python 3.5 issues fixed.\
    - std::array support added for Ruby and Python.\
    - shared_ptr support added for Ruby.\
    - Minor improvements for CFFI, Go, Java, Perl, Python, Ruby.
    :::

**2015/08/03** - [SWIG-3.0.7 released](https://sourceforge.net/p/swig/news/2015/08/swig-307-released/)

:   ::: {.markdown_content}
    SWIG-3.0.7 release summary:\
    *Add support for Octave-4.0.0.\
    * Remove potential Android security exploit in generated Java
    classes.\
    \* Minor new features and bug fixes.
    :::

**2015/07/05** - [SWIG-3.0.6 released](https://sourceforge.net/p/swig/news/2015/07/swig-306-released/)

:   ::: {.markdown_content}
    SWIG-3.0.6 is mostly a stability release.

    Release summary:\
    - Stability and regression fixes.\
    - Fixed parsing of C++ corner cases.\
    - Language improvements and bug fixes for C\#, Go, Java, Lua,
    Python, R.
    :::

[More news](news.php)

------------------------------------------------------------------------

Feedback and questions concerning this site should be posted to the
[swig-devel](mail.html) mailing list.

Last modified : Thu Apr 18 20:11:49 2019
