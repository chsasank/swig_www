---
layout: default
title: News
nav_order: 7
last_modified_date: Sat May 13 14:25:49 2017
---

# SWIG News

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

**2015/03/07** - [Defending the GPL](https://sourceforge.net/p/swig/news/2015/03/defending-the-gpl/)

:   ::: {.markdown_content}
    SWIG is a proud member of the Software Freedom Conservancy who has
    recently
    [announced](http://sfconservancy.org/news/2015/mar/05/vmware-lawsuit)
    that they will be supporting a lawsuit to defend an alleged
    violation of the GNU General Public License (GPL). Ensuring this
    software license, the same one that protects the SWIG source code,
    is not abused and is actively defended in a court of law is
    important for everyone using the license.

    Conservancy is supporting Christoph Hellwig\'s lawsuit against
    VMware over GPL violations on Linux. VMware have stated that they
    would not comply with the GPL after many patient years of
    negotiations by Christoph and the Conservancy. More information is
    in the [Conservancy\'s FAQ on the
    lawsuit](http://sfconservancy.org/linux-compliance/vmware-lawsuit-faq.html).

    If you have benefited or enjoyed the fruits of SWIG, it is because
    the SWIG developer\'s chose to use a software license to ensure it
    remains freely available. Please consider supporting Christoph and
    Conservancy including their [fund raising
    appeal](http://sfconservancy.org/linux-compliance/vmware-lawsuit-appeal.html)
    to defend our license.

    William Fulton\
    SWIG lead maintainer
    :::

**2015/02/01** - [SWIG-3.0.5 released](https://sourceforge.net/p/swig/news/2015/02/swig-305-released/)

:   ::: {.markdown_content}
    We are pleased to announce SWIG-3.0.5 has been released with the
    addition of support for Scilab.

    This version also contains:

    -   An important Python fix for a regression in SWIG-3.0.3 when
        wrapping C++ default arguments.
    -   Minor improvements for C\#, Go, Octave, PHP and Python.

    SWIG-3.0.4 was also released recently and contained part of the
    Python fix for the regression mentioned above. Python users should
    definitely rather use 3.0.5.
    :::

**2014/12/31** - [SWIG-3.0.3 released](https://sourceforge.net/p/swig/news/2014/12/swig-303-released/)

:   ::: {.markdown_content}
    SWIG-3.0.3 release summary:\
    - Add support for C++11 strongly typed enumerations.\
    - Numerous bug fixes and minor enhancements for C\#, D, Go, Java,\
    Javascript, PHP, Perl and Python wrappers.

    More detailed release notes can be seen at
    <http://swig.org/release.html>
    :::

**2014/06/04** - [SWIG-3.0.2 released](https://sourceforge.net/p/swig/news/2014/06/swig-302-released/)

:   ::: {.markdown_content}
    This release has been made to fix a bug during installation, but it
    also includes a couple of other rather minor changes.
    :::

**2014/05/27** - [SWIG-3.0.1 released](https://sourceforge.net/p/swig/news/2014/05/swig-301-released/)

:   ::: {.markdown_content}
    SWIG-3.0.1 is another milestone release as it is the first version
    to contain support for Javascript.

    Release summary:

    -   Javascript module added. This supports JavascriptCore
        (Safari/Webkit), v8 (Chromium) and node.js currently.
    -   A few notable regressions introduced in 3.0.0 have been fixed -
        in Lua, nested classes and parsing of operator \<\<.
    -   The usual round of bug fixes and minor improvements for C\#,
        GCJ, Go, Java, Lua, PHP and Python.
    :::

**2014/03/16** - [SWIG-3.0.0 released](https://sourceforge.net/p/swig/news/2014/03/swig-300-released/)

:   ::: {.markdown_content}
    This is a major new release focusing primarily on C++ improvements.

    -   C++11 support added. Please see documentation for details of
        supported\
        features: <http://www.swig.org/Doc3.0/CPlusPlus11.html>
    -   Nested class support added. This has been taken full advantage
        of in\
        Java and C\#. Other languages can use the nested classes, but
        require\
        further work for a more natural integration into the target
        language.\
        We urge folk knowledgeable in the other target languages to
        step\
        forward and help with this effort.
    -   Lua: improved metatables and support for %nspace.
    -   Go 1.3 support added.
    -   Python import improvements including relative imports.
    -   Python 3.3 support completed.
    -   Perl director support added.
    -   C\# .NET 2 support is now the minimum. Generated using
        statements are\
        replaced by fully qualified names.
    -   Bug fixes and improvements to the following languages:\
        C\#, Go, Guile, Java, Lua, Perl, PHP, Python, Octave, R, Ruby,
        Tcl
    -   Various other bug fixes and improvements affecting all
        languages.
    -   Note that this release contains some backwards incompatible
        changes\
        in some languages.
    -   Full detailed release notes are in the changes file.\
        See <http://swig.org/release.html.>
    :::

**2014/02/09** - [SWIG-2.0.12 released](https://sourceforge.net/p/swig/news/2014/02/swig-2012-released/)

:   ::: {.markdown_content}
    SWIG-2.0.12 summary:\
    - This is a maintenance release backporting some fixes from the
    pending 3.0.0 release.\
    - Octave 3.8 support added.\
    - C++11 support for new versions of erase/insert in the STL
    containers.\
    - Compilation fixes on some systems for the generated Lua, PHP,
    Python and R wrappers.
    :::

**2013/09/15** - [SWIG-2.0.11 released](https://sourceforge.net/p/swig/news/2013/09/swig-2011-released/)

:   ::: {.markdown_content}
    SWIG-2.0.11 summary:\
    - Minor bug fixes and enhancements mostly in Python, but also\
    C\#, Lua, Ocaml, Octave, Perl, PHP, Python, R, Ruby, Tcl.
    :::

**2013/05/27** - [SWIG-2.0.10 released](https://sourceforge.net/p/swig/news/2013/05/swig-2010-released/)

:   ::: {.markdown_content}
    SWIG-2.0.10 summary:\
    - Ruby 1.9 support is now complete.\
    - Add support for Guile 2.0 and Guile 1.6 support (GH interface)
    has\
    been dropped.\
    - Various small language neutral improvements and fixes.\
    - Various bug fixes and minor improvements specific to C\#, CFFI,
    D,\
    Java, Octave, PHP, Python,\
    - Minor bug fix in ccache-swig.\
    - Development has moved to Github with Travis continuous
    integration\
    testing - patches using <https://github.com/swig/swig> are welcome.
    :::

**2013/05/03** - [SWIG license explanation](https://sourceforge.net/p/swig/news/2013/05/swig-license-explanation/)

:   ::: {.markdown_content}
    We have recently updated the SWIG legal page to provide
    clarification on the SWIG license. There has been some confusion as
    to how the GPL license may or may not affect the code generated by
    SWIG. Please take a look at the updated [SWIG legal
    page](http://www.swig.org/legal.html).

    We are indebted to the [Software Freedom Law
    Center](http://softwarefreedom.org/) for all the help given in
    providing the legal explanations and for originally helping set up
    the license for version 2.0.
    :::

**2013/01/03** - [SWIG on Github](https://sourceforge.net/p/swig/news/2013/01/swig-on-github/)

:   ::: {.markdown_content}
    With the new year we have switched SWIG development to a new
    development model - Git on Github. The old Subversion history
    (including the even older CVS history) has been migrated and is now
    viewable in Github - <https://github.com/swig/swig>. If you have
    used SWIG we would really appreciate improvements you have made for
    incorporation into the mainline SWIG releases. So, feel free to use
    Github to fork and send your pull requests or patches.

    Improvements to the documentation are also very welcome - the html
    source can be found at
    <https://github.com/swig/swig/tree/master/Doc/Manual>.

    Information for getting going is on the SWIG website: [SWIG Bleeding
    Edge](http://www.swig.org/svn.html).

    We have also turned on the new SourceForge Allura system which is
    much slicker than the old SourceForge for submitting bugs/patches -
    [SWIG on SourceForge](https://sourceforge.net/projects/swig/).

    Happy new year!\
    William
    :::

**2012/12/16** - [SWIG-2.0.9 released](https://sourceforge.net/p/swig/news/2012/12/swig-209-released/)

:   ::: {.markdown_content}
    SWIG-2.0.9 summary:\
    - Improved typemap matching.\
    - Ruby 1.9 support is much improved.\
    - Various bug fixes and minor improvements in C\#, CFFI, Go, Java,\
    Modula3, Octave, Perl, Python, R, Ruby, Tcl and in ccache-swig.
    :::

**2012/11/07** - [Summer of Code 2012](https://sourceforge.net/p/swig/news/2012/11/summer-of-code-2012/)

:   ::: {.markdown_content}
    GSoC 2012 was SWIG\'s third Summer of Code, and this year we\
    received five slots for projects related to SWIG. Out of five,\
    four students completed the program successfully with valuable\
    additions to SWIG.

    Dmitry Kabak, mentored by Marko Klopcic, worked on SWIG\
    internals to parse the source code documentation comments within\
    the C/C++ header files and use them to document the target\
    language wrapper classes/functions. Dmitry\'s efforts\
    complemented the existing support added in GSoC 2008. In\
    summary, all previously known bugs have been fixed and the\
    original source code for comment translation was re-factored to\
    improve performance and maintainability. Parsing of C/C++ source\
    code has been improved, so that every declaration/definition can\
    now be commented. Translation of Doxygen tags to Javadoc and\
    Python docstrings has been improved and corresponding regression\
    tests have been implemented. The project mentor, Marko Klopcic\
    has some great ideas for the future GSoC. The work can be tried\
    out on the branch gsoc2012-doxygen.

    Leif Middelschulte, mentored by Vadim Zeitlin, worked on the C\
    target language module for SWIG. Leif has improved the module\
    to a working level. He also rationalized and documented the use\
    of C typemaps and more generally improved documentation and\
    testing. Finally, the generated C bindings were made more\
    type-safe to disallow passing of objects of different types.\
    Unfortunately, a lot of work still remains to be done. In\
    particular, many problems remain with template support. Leif\'s\
    GSoC work can be accessed in the subversion branch gsoc2012-c.

    Neha Narang, mentored by Oliver Buchtala, has worked on a\
    JavaScript module for SWIG, particularly addressing the\
    JavaScript Core engine. The work is based on prototype work\
    from Ashish Sharma (JSC) and Oliver Buchtala (V8, design for\
    unified module). Neha implemented basic features: global\
    functions and variables, classes, single inheritance, constants,\
    enums and exception handling. Taking her programming skills in\
    consideration, some tasks needed more support where Oliver\
    complemented her work: overloaded functions, using unified\
    typemap library, namespaces. She added 12 common examples and\
    started the test-suite writing 32 tests. Additionally, she\
    created detailed documentation describing design rationale and\
    module usage. The module is in a good shape considering it is a\
    new module, but some tasks are left. The next tasks will enhance\
    the test-suite, and add director support and bring the generator\
    addressing the V8 engine into a similar state. Neha\'s work in\
    GSoC is available in the branch gsoc2012-javascript.

    Swati Sharma, mentored by Ashish Sharma, spent her summer\
    working on the Objective C module for SWIG. SWIG had initial\
    support for generating Objective C wrappers over C++ which was\
    added in GSoC 2009. These wrappers will be used to make C/C++\
    objects available to MacOS X, iphone and ipad applications. The\
    goal for the summer was to have a cleaner implementation and get\
    the code in a good shape for merging into trunk. Swati finished\
    close to meeting the goal with an almost completely re- written,\
    clean implementation fixing many rough edges. We now have a\
    more comprehensive set of typemaps for Objective-C and C++ type\
    conversions. Almost 90% of the test-suite works and a number of\
    new runtime tests have been added. Makefiles have been\
    reorganized, and the structure of the generated code redesigned\
    to equally support Apple\'s cocoa framework on MacOS X and\
    GNUStep on Linux/Windows. Swati is very keen to add more\
    features in the coming months, especially, the director support,\
    support for clang, and updated module documentation. Swati\'s\
    work can be accessed in the branch gsoc2012-objc.

    We would like to thank Google for sponsoring the Summer of Code.\
    A special thanks to all the mentors for their hard work and\
    William Fulton, the co-administrator, for his guidance and\
    support.

    By: Ashish Sharma, GSoC 2012 administrator for SWIG
    :::

**2012/08/20** - [SWIG-2.0.8 released](https://sourceforge.net/p/swig/news/2012/08/swig-208-released/)

:   ::: {.markdown_content}
    SWIG-2.0.8 summary:\
    - Fix a couple of regressions introduced in 2.0.5 and 2.0.7.\
    - Improved using declarations and using directives support.\
    - Minor fixes/enhancements for C\#, Java, Octave, Perl and Python.
    :::

**2012/05/26** - [SWIG-2.0.7 released](https://sourceforge.net/p/swig/news/2012/05/swig-207-released/)

:   ::: {.markdown_content}
    SWIG-2.0.7 summary:\
    - Important regression fixes since 2.0.5 for typemaps in general
    and\
    in Python.\
    - Fixes and enhancements for Go, Java, Octave and PHP.
    :::

**2012/04/30** - [SWIG-2.0.6 released](https://sourceforge.net/p/swig/news/2012/04/swig-206-released/)

:   ::: {.markdown_content}
    This release fixes a bug in SWIG-2.0.5, please use SWIG-2.0.6
    instead.

    SWIG-2.0.6 summary:\
    - Regression fix for Python STL wrappers on some systems.
    :::

**2012/04/24** - [Summer of Code 2012 projects](https://sourceforge.net/p/swig/news/2012/04/summer-of-code-2012-projects/)

:   ::: {.markdown_content}
    Google has announced the list of accepted students for the Google
    Summer of Code program. SWIG was given 5 slots this year the SWIG
    developer community has chosen the following projects which will be
    worked on over the next 4 months:

    \"SWIG\'s Scilab 6.0 Backend\" - Wolfgang Frisch\
    \"Enhance Objective C support\" - Swati Sharma\
    \"Get the C backend in shape and into trunk\" - Leif Middelschulte\
    \"New module for Javascript\" - Neha Narang\
    \"Source Code Documentation Comments\" - Dmitry Kabak

    Congratulations to Wolfgang, Swati, Leif, Neha and Dmitry.

    An abstract for every project is available here:
    <http://google-melange.appspot.com/org/home/google/gsoc2012/swig>

    Anyone interested in these projects, is welcome to drop by on our
    IRC channel - \#swig-gsoc on irc.freenode.net\
    or follow the development of them on the swig-devel mailing list -
    <http://www.swig.org/mail.html> .
    :::

**2012/04/19** - [SWIG-2.0.5 released](https://sourceforge.net/p/swig/news/2012/04/swig-205-released/)

:   ::: {.markdown_content}
    SWIG-2.0.5 summary:\
    - Official Android support added including documentation and
    examples.\
    - Improvements involving templates:\
    1) Various fixes with templates and typedef types.\
    2) Some template lookup problems fixed.\
    3) Templated type fixes to use correct typemaps.\
    - Autodoc documentation generation improvements.\
    - Python STL container wrappers improvements including addition of\
    stepped slicing.\
    - Approximately 70 fixes and minor enhancements for the following\
    target languages: AllegroCL, C\#, D, Go, Java, Lua, Ocaml, Octave,\
    Perl, PHP, Python, R, Ruby, Tcl, Xml.
    :::

**2012/03/24** - [SWIG in Google Summer of Code 2012](https://sourceforge.net/p/swig/news/2012/03/swig-in-google-summer-of-code-2012/)

:   ::: {.markdown_content}
    SWIG has been accepted on the Google Summer of Code program for the
    third time. This is an opportunity for budding open source
    programmers to get paid for coding. If you are a student and
    interested please take a look at
    <http://codewrapper.com/wiki/index.php?title=SWIG>\_GSoC_2012_ideas_page
    and <http://www.google-melange.com/gsoc/homepage/google/gsoc2012>
    for further details. Applications must be in by 6 April 2012.
    :::

**2011/05/21** - [SWIG-2.0.4 released](https://sourceforge.net/p/swig/news/2011/05/swig-204-released/)

:   ::: {.markdown_content}
    SWIG-2.0.4 release summary:\
    - This is mainly a Python oriented release including support for
    Python\
    built-in types for superior performance with the new -builtin
    option.\
    The -builtin option is especially suitable for performance-critical\
    libraries and applications that call wrapped methods repeatedly.\
    See the python-specific chapter of the SWIG manual for more info.\
    - Python 3.2 support has also been added and various Python bugs
    have\
    been fixed.\
    - Octave 3.4 support has also been added.\
    - There are also the usual minor generic improvements, as well as
    bug\
    fixes and enhancements for D, Guile, Lua, Octave, Perl and Tcl.
    :::

**2011/03/29** - [SWIG-2.0.3 released](https://sourceforge.net/p/swig/news/2011/03/swig-203-released/)

:   ::: {.markdown_content}
    SWIG-2.0.3 has been released. This is a bug fix release including a
    couple of fixes for regressions in the 2.0 series.
    :::

**2011/02/20** - [SWIG-2.0.2 released](https://sourceforge.net/p/swig/news/2011/02/swig-202-released/)

:   ::: {.markdown_content}
    SWIG-2.0.2 has been released and includes the following changes:

    \- Support for the D language has been added.\
    - Various bug fixes and minor enhancements.\
    - Bug fixes particular to the Clisp, C\#, Go, MzScheme, Ocaml, PHP,
    R, Ruby target languages.
    :::

**2010/10/04** - [SWIG-2.0.1 released](https://sourceforge.net/p/swig/news/2010/10/swig-201-released/)

:   ::: {.markdown_content}
    SWIG-2.0.1 has been released and includes the following changes:

    \- Support for the Go language has been added.\
    - New regular expression (regex) encoder for renaming symbols based
    on the Perl Compatible Regular Expressions (PCRE) library -
    <http://pcre.org> .\
    - Numerous fixes in reporting file and line numbers in error and
    warning messages.\
    - Various bug fixes and improvements in the C\#, Lua, Perl, PHP,
    Ruby and Python language modules.
    :::

**2010/06/03** - [SWIG-2.0.0 released](https://sourceforge.net/p/swig/news/2010/06/swig-200-released/)

:   ::: {.markdown_content}
    SWIG-2.0.0 has been released. The following are the main changes:

    \- License changes, see LICENSE file and
    <http://www.swig.org/legal.html> .\
    - Much better nested class/struct support.\
    - Much improved template partial specialization and explicit
    specialization handling.\
    - Namespace support improved with the \'nspace\' feature where
    namespaces can be automatically translated into Java packages or C\#
    namespaces.\
    - Improved typemap and symbol table debugging.\
    - Numerous subtle typemap matching rule changes when using the
    default (SWIGTYPE) type. These now work much like C++ class template
    partial specialization matching.\
    - Other small enhancements for typemaps. Typemap fragments are also
    now official and documented.\
    - Warning and error display refinements.\
    - Wrapping of shared_ptr is improved and documented now.\
    - Numerous C++ unary scope operator (::) fixes.\
    - Better support for boolean expressions.\
    - Various bug fixes and improvements in the Allegrocl, C\#, Java,
    Lua, Octave, PHP, Python, R, Ruby and XML modules.
    :::

**2010/04/20** - [SWIG joins the Software Freedom Conservancy](https://sourceforge.net/p/swig/news/2010/04/swig-joins-the-software-freedom-conservancy/)

:   ::: {.markdown_content}
    The Software Freedom Conservancy has just announced that SWIG has
    been accepted as a member of the Conservancy -
    <http://sfconservancy.org/news/2010/apr/20/swig-joins/> . Being part
    of the Conservancy and all the good work it does for free and open
    source software is great news for SWIG. The Conservancy provides
    many benefits such as a formal legal structure and will help ensure
    the vitality of SWIG as the Conservancy is able to handle donations
    to the SWIG project. Please visit our new
    <http://www.swig.org/donate.html> donations page.
    :::

**2009/09/23** - [SWIG\'s Second Summer of code](https://sourceforge.net/p/swig/news/2009/09/swigs-second-summer-of-code/)

:   ::: {.markdown_content}
    SWIG is a programmer\'s tool designed to make it easier to use C and
    C++ code from other popular programming languages such as Python,
    Perl, Ruby, PHP, Java, and C\#. 2009 was SWIG\'s second Summer of
    Code, and this year we mentored five projects related to SWIG. All
    five students were very active over the summer period and produced
    some great new features. In no particular order:

    Matevz Jekovec has been busy working at the coal face of SWIG to add
    support for C++0x, the forthcoming C++ standard. Matevz has managed
    to achieve close to full support for C++0x. The C++0x Wikipaedia
    article <http://en.wikipedia.org/wiki/C%2B%2B0x> details the
    numerous planned new C++0x features and Matev? has put together a
    SWIG C++0x page
    (<http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2009-matevz/Doc/Manual/Cpp0x.html>)
    documenting the new SWIG support for each of these. In summary the
    enhanced C++ language can now be parsed by SWIG, which in itself is
    a great step. There is much more than just this though, as most of
    the information parsed is used to create useful wrappers of C++0x
    code. The work can be tried out on the C++0x branch
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2009-matevz>
    which should be merged fairly soon into a forthcoming release.

    Miklos Vajna has been working on SWIG\'s PHP support to implement an
    advanced SWIG feature already supported for most other target
    languages, but not PHP. The feature is called \"directors\" and
    allows cross-language polymorphism - wrapped C++ classes can be
    subclassed in PHP and virtual method calls work in the natural way,
    whether they\'re made from PHP or C++ code. You can read more in the
    new PHP Director documentation
    <http://www.swig.org/Doc1.3/Php.html>\#Php_nn3 . Miklos made such
    great progress that we were able to merge this support into SWIG
    1.3.40, which was released even before the Summer of Code finished.
    Miklos also spent some time working on improving SWIG\'s testsuite
    for PHP, and fixing bugs in the PHP support.

    Ashish Sharma spent the summer adding support for Objective-C as a
    new target language. Objective-C is a major language on the Mac OS X
    platform. This means that now SWIG can be used to generate
    Objective-C wrappers over C++ code. In particular the wrappers
    include proxy classes, which preserve the class hierarchy from the
    C++ code. Ultimately this means that from the user\'s perspective,
    proxy objects look no different to objects originally written in
    Objective-C. Adding a new target language is quite a considerable
    task and Ashish is keen to add plenty more improvements over the
    coming months. Ashish\'s work is in Subversion and can be accessed
    in the ashishs99 branch
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2009-ashishs99>
    .

    Baozeng Ding has also added a new target language, in this case for
    the Scilab language, a free numerical computing package. He has
    coded up support for all the C features: variables, functions,
    constants, enums, structs, unions, pointers and arrays and also
    intends to develop it further in the near future. Documentation for
    SWIG and Scilab can be viewed online direct from Baozeng\'s
    Subversion branch
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2009-sploving/Doc/Manual/Scilab.html>
    .

    Kosei Moriyama has been working on Perl bindings for the Xapian
    library using SWIG, to replace some existing bindings implemented by
    hand. He\'s achieved almost complete compatibility with the API of
    the existing bindings (the only real omission is callbacks which are
    waiting for completion of director support for Perl in SWIG). He has
    also wrapped features which weren\'t previously accessible from
    Perl. You can view Kosei\'s work online in his Subversion branch
    <http://trac.xapian.org/browser/branches/gsoc2009-kosei> .

    Finally, many thanks to Google for sponsoring the summer of code and
    a special thanks for all the hard work done by the students, mentors
    and Olly Betts, the co-administrator.
    :::

**2009/08/18** - [SWIG-1.3.40 released](https://sourceforge.net/p/swig/news/2009/08/swig-1340-released/)

:   ::: {.markdown_content}
    SWIG-1.3.40 has been release. A summary of changes is as follows:

    \- SWIG now supports directors for PHP.\
    - PHP support improved in general.\
    - Octave 3.2 support added.\
    - Various bug fixes/enhancements for Allegrocl, C\#, Java, Octave,
    Perl, Python, Ruby and Tcl.\
    - Other generic fixes and minor new features.
    :::

**2009/04/21** - [Summer of code 2009 accepted projects](https://sourceforge.net/p/swig/news/2009/04/summer-of-code-2009-accepted-projects/)

:   ::: {.markdown_content}
    The students accepted into the Google Summer of Code have now been
    announced. SWIG has been allocated five student slots by Google and
    we have chosen the following five projects/students which will be
    developed over the next four months:\

    \"Add support for Scilab language\" - Baozeng Ding\
    \"C++0x support for Swig\" - Matevz Jekovec\
    \"Implement Perl binding for Xapian using SWIG\" - Kosei MORIYAMA\
    \"Objective C Wrapper Generator over C++ using SWIG\" - Ashish
    Sharma\
    \"Director support for PHP\" - Miklos Vajna\

    An abstract for each project is available at
    <http://socghop.appspot.com/org/home/google/gsoc2009/swig>\

    Congratulations to Baozeng, Matevz, Kosei, Ashish and Miklos, we set
    some fairly high standards for acceptance this year and you have all
    done well to meet these standards. We hope that your quality
    proposals will result in useful enhancements by the end of the
    summer.

    For anyone interested in any of these projects, you are welcome to
    follow the development of them on the swig-devel mailing list -
    <http://www.swig.org/mail.html> . Also feel free to drop by our IRC
    channel to discuss or just say hello - \#swig-gsoc on
    irc.freenode.net.\

    William and Olly\
    SWIG Summer of Code administrators 2009
    :::

**2009/03/21** - [SWIG-1.3.39 released](https://sourceforge.net/p/swig/news/2009/03/swig-1339-released/)

:   ::: {.markdown_content}
    SWIG-1.3.39 has been release. A summary of changes is shown below.

    \- Some new small feature enhancements.\
    - Improved C\# std::vector wrappers.\
    - Bug fixes: mainly Python, but also Perl, MzScheme, CFFI, Allegrocl
    and Ruby
    :::

**2009/03/19** - [SWIG participating in Summer of Code 2009](https://sourceforge.net/p/swig/news/2009/03/swig-participating-in-summer-of-code-2009/)

:   ::: {.markdown_content}
    We are excited to announce that SWIG has been accepted onto the
    Google Summer of Code program for the second year running. This is a
    chance for SWIG to be enhanced in any way that you would like it to.

    The Summer of Code program is designed to get new people involved in
    free/open-source software and get paid for it. Either become a
    student and code up the changes or if you have an interest in a
    particular feature being implemented, become a mentor and get paid
    for looking after a student. The ideas page at
    <http://code.google.com/p/swig-gsoc/wiki/ProjectIdeas> contains some
    suggestions for SWIG, but any reasonable suggestions will be
    considered. Please chat to us on IRC at \#swig-gsoc on
    irc.freenode.net or email us on the mailing lists. See
    <http://socghop.appspot.com/> for further general information.
    :::

**2009/02/01** - [SWIG-1.3.38 released](https://sourceforge.net/p/swig/news/2009/02/swig-1338-released/)

:   ::: {.markdown_content}
    SWIG-1.3.38 has been released. It contains an output directory
    regression fix and other minor bug fixes.
    :::

**2009/01/15** - [SWIG: 1.3.37 released](https://sourceforge.net/p/swig/news/2009/01/swig-1337-released/)

:   ::: {.markdown_content}
    SWIG is a software development tool that reads C/C++ header files
    and generates wrapper code to make C/C++ code accessible from other
    languages including Perl, Python, Tcl, Ruby, PHP, Java, Ocaml, Lua,
    C\#, Modula-3, R, Octave and Scheme & Lisp variants.

    Apart from the usual round of bug fixes and minor new features there
    are a couple of big new features in this release. The main changes
    are:

    \- Python 3 support added\
    - SWIG now ships with a version of ccache that can be used with
    SWIG. This enables the files generated by SWIG to be cached so that
    repeated use of SWIG on unchanged input files speeds up builds quite
    considerably.\
    - PHP 4 support removed and PHP support improved in general\
    - Improved C\# array support\
    - Numerous Allegro CL improvements
    :::

**2008/10/08** - [SWIG\'s First Summer of Code](https://sourceforge.net/p/swig/news/2008/10/swigs-first-summer-of-code/)

:   ::: {.markdown_content}
    SWIG is a programmers tool for semi-automating the calls to C or C++
    code from almost any other programming language. The idea is to feed
    C/C++ header files into SWIG and SWIG then generates the \'glue\'
    code so that your C/C++ library can be used from another language
    such as Python, Java, C\#, Ruby, Perl etc. In fact there are
    implementations for supporting over 20 different of these target
    languages. The summer of code students have had a productive summer
    and have extended the number of languages and features supported in
    SWIG\'s first Google Summer of Code.

    Haoyu Bai has added support for the upcoming Python 3 release.
    Python is the most popular target language amongst SWIG users and no
    doubt this addition will be much appreciated by those who are
    thinking of upgrading to Python 3. Also Haoyu has provided new
    Python 3 features which make coding faster and simpler when using
    Python extension code. The main features added are function
    annotations, buffer interfaces and abstract base classes and are
    outlined in more detail here:
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2008-bhy/Doc/Manual/Python.html>\#Python_python3support

    Jan Jezabek has added a new \'language\' module providing Windows
    Component Object Model (COM) support. This new module makes it
    possible for any COM enabled language to easily call into C or C++
    libraries. The COM module in SWIG is more powerful than most as it
    ultimately provides support for more than one language as there are
    numerous languages that can call into COM libraries. Compiled
    languages such as Visual Basic and scripting languages, such as
    JScript, VBA and VBScript that can run on the Windows Scripting Host
    are probably the most popular to benefit. A great use will be the
    ease of making C/C++ libraries available in applications supporting
    the various Basic dialects, such as OpenOffice.org and Microsoft
    Office. SWIG makes it easy to utilise more advanced C++ code, such
    as templates, and the COM module is no different here as Jan has
    added in very comprehensive coverage of the C and C++ languages,
    full details here:
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2008-jezabek/Doc/Manual/COM.html>

    Maciej Drwal has added a module for calling C++ code from C code. It
    is now possible to automatically create a flattened API of C++
    classes so that the C++ functionality is available in the form of
    easy to use C structs and global functions. For example, features
    such as C++ template classes / functions are easily callable from C.
    One cool part of this project is the graceful handling of C++
    exceptions in the calling C code. Some introductory documentation is
    available here:
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2008-maciekd/Doc/Manual/C.html>

    Cheryl Foil has added an interesting feature to improve code
    documentation in the target language. This works when C/C++ code is
    documented using the industry standard Doxygen tool for annotating
    methods, classes, variables etc. The new feature extracts the
    Doxygen comments from the code for use by one of the many target
    languages. Cheryl has added initial support for Java so that the
    Doxygen comments are turned into JavaDoc comments embedded into the
    generated Java wrappers, see
    <http://swig.svn.sourceforge.net/viewvc/swig/branches/gsoc2008-cherylfoil/Doc/Manual/Doxygen.html>

    Lastly, many thanks to the mentors involved in making this happen,
    Ian Appru, Olly Betts, Richard Boulton and William Fulton and
    finally to Google for funding a great programme.
    :::

**2008/06/24** - [SWIG-1.3.36 released](https://sourceforge.net/p/swig/news/2008/06/swig-1336-released/)

:   ::: {.markdown_content}
    SWIG-1.3.36 has been released. The major changes are listed below.

    \- Enhancement to directors to wrap all protected members\
    - Optimisation feature for objects returned by value\
    - A few bugs fixes in the PHP, Java, Ruby, R, C\#, Python, Lua and
    Perl modules\
    - Other minor generic bug fixes
    :::

**2008/05/03** - [Summer of Code students](https://sourceforge.net/p/swig/news/2008/05/summer-of-code-students/)

:   ::: {.markdown_content}
    2008/04/21 The students accepted into the Google Summer of Code have
    now been announced. SWIG has managed to get four slots and we have
    chosen the following four projects/students:

    \* \"SWIG\'s Python 3.0 Backend\" - Haoyu Bai tutored by Richard
    Boulton\
    \* \"C target language backend\" - Maciej Drwal tutored by William
    Fulton\
    \* \"Comment \'Translator\' for SWIG\" - Cheryl Marie Foil tutored
    by Olly Betts\
    \* \"Support for generating COM wrappers\" - Jan Jezabek tutored by
    Ian Appru

    The competition was tough and although it was difficult choosing the
    projects, these four were our strongest, so congratulations and
    welcome to Haoyu, Jan, Cheryl and Maciej. Further details on the
    Google SWIG page - <http://code.google.com/soc/2008/swig/about.html>
    .
    :::

**2008/05/03** - [SWIG-1.3.35 released](https://sourceforge.net/p/swig/news/2008/05/swig-1335-released/)

:   ::: {.markdown_content}
    2008/04/07 SWIG-1.3.35 has been released. This release adds Octave
    to the list of languages modules that SWIG can generate wrappers
    for. This release also contains a few bug fixes and regression fixes
    from the previous release.
    :::

**2008/05/03** - [SWIG accepted onto Google Summer of Code](https://sourceforge.net/p/swig/news/2008/05/swig-accepted-onto-google-summer-of-code/)

:   ::: {.markdown_content}
    2008/03/18 SWIG is one of 175 open source organizations that have
    been accepted onto the Google Summer of Code (GSoC) 2008. GSoC is a
    program to pay students and in the process benefit open source -
    <http://code.google.com/opensource/gsoc/2008/faqs.html> . Students
    interested in submitting an application to work on SWIG are invited
    to look at the ideas page
    (<http://www.dabeaz.com/cgi-bin/wiki.pl?DeveloperInfo/GoogleSummerOfCode>)
    and then discuss them on the mailing lists before submitting a
    project proposal.
    :::

**2008/05/03** - [SWIG-1.3.34 released](https://sourceforge.net/p/swig/news/2008/05/swig-1334-released/)

:   ::: {.markdown_content}
    2008/02/27 SWIG-1.3.34 has been released. This release adds
    shared_ptr support for Python and fixes a number of various other
    bugs.
    :::

**2008/05/03** - [SWIG-1.3.33 released](https://sourceforge.net/p/swig/news/2008/05/swig-1333-released/)

:   ::: {.markdown_content}
    2007/11/23 SWIG-1.3.33 has been released and fixes a few regressions
    introduced into version 1.3.32.
    :::

**2008/05/03** - [SWIG-1.3.32 released](https://sourceforge.net/p/swig/news/2008/05/swig-1332-released/)

:   ::: {.markdown_content}
    2007/11/15 SWIG-1.3.32 has been released. This release contains over
    a hundred bug fixes and improvements to most language modules.
    :::

\<\< [Full News Archives](https://sourceforge.net/p/swig/news/) \>\>

------------------------------------------------------------------------

Feedback and questions concerning this site should be posted to the
[swig-devel](mail.html) mailing list.

