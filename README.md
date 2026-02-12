# Awesome D [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 436,832 | 🐛 67 | 📅 2026-01-28 with stars

A curated list of awesome D frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 282,462 | 🐛 17 | 🌐 Python | 📅 2026-02-10.

Most documents and links are collected from the [D forum](https://forum.dlang.org), the [D wiki](https://wiki.dlang.org), and the [D package repository](https://code.dlang.org). Exploring GitHub is also helpful, as many libraries are hosted there. If you know of an interesting D project, please let us know via [GitHub issues](https://github.com/dlang-community/awesome-d/issues) ⭐ 743 | 🐛 3 | 🌐 D | 📅 2026-02-04 or by [editing this file](https://github.com/dlang-community/awesome-d/edit/master/README.md) ⭐ 743 | 🐛 3 | 🌐 D | 📅 2026-02-04.

## Contents

* Basic Information
  * [Official Website](#official-website)
  * [Getting Help](#getting-help)
  * [People](#people)
  * [Events](#events)
  * [Organizations](#organizations)
* Documents
  * [Books](#books)
  * [Tutorials](#tutorials)
  * [Blogs](#blogs)
  * [Articles](#articles)
* Language Related
  * [Package Management](#package-management)
  * [Compilers](#compilers)
  * [Alternative / WIP Compilers](#alternative--wip-compilers)
  * [Dev Tools](#dev-tools)
  * [Build Tools](#build-tools)
  * [IDEs & Editors](#ides--editors)
  * [Lexers, Parsers & Generators](#lexers-parsers--generators)
  * [Preprocessors](#preprocessors)
  * [Version Managers](#version-managers)
* Continuous Integration
  * [GitHub Actions](#github-actions)
  * [Testing Frameworks](#testing-frameworks)
* Languages
  * [Programming Languages](#programming-languages)
* OS
  * [Operating Systems](#operating-systems)
  * [Bare Metal / Kernel Development](#bare-metal--kernel-development)
* Common
  * [General Containers](#general-containers)
  * [Core Utilities](#core-utilities)
* Networking / Web
  * [Web Frameworks](#web-frameworks)
  * [Data Serialization](#data-serialization)
* Database
  * [Database Clients](#database-clients)
* CLI
  * [CLI Libraries](#cli-libraries)
  * [CLI Applications](#cli-applications)
* GUI
  * [GUI Libraries](#gui-libraries)
  * [GUI Applications](#gui-applications)
* Game Development
  * [Game Bindings](#game-bindings)
  * [Game Libraries](#game-libraries)
  * [Games](#games)
* Internationalization (i18n) / Globalization
  * [Internationalization](#internationalization)
* Image Processing
  * [Image Processing](#image-processing)
* Machine Learning
  * [Machine Learning](#machine-learning)
  * [Parallel Computing](#parallel-computing)
* Scientific
  * [Scientific](#scientific)
  * [Language Processing](#language-processing)
* Others
  * [Text Processing](#text-processing)
  * [Logging](#logging)
  * [Configuration](#configuration)
  * [BlogEngine](#blog-engine)
  * [Dependency Injection](#dependency-injection)
  * [Cryptography](#cryptography)
  * [Unmaintained](#unmaintained)

## Official Websites

*Official website URLs for D.*

* [dlang.org](https://dlang.org) - Official website for D.
* [wiki.dlang.org](https://wiki.dlang.org) - Official wiki for D.
* [blog.dlang.org](https://dlang.org/blog/) - Official blog for D.
* [forum.dlang.org](https://forum.dlang.org/) - Official forum for D. Many interesting discussions occurring on a daily basis.
* [code.dlang.org](https://code.dlang.org) - Official library registry for D.
* [GitHub organization](https://github.com/dlang) - Official GitHub organization for D. Repository for all official D tools & code.
* [Issue tracker](https://github.com/dlang) – Official issue tracker for D. Older reports can be found in the [archived tracker](https://issues.dlang.org/).
* [Language specification](https://dlang.org/spec/spec.html) - The D programming language specification.

## Getting Help

*For when you're stuck.*

* [Official D Forum Learn Group](https://forum.dlang.org/group/learn) - Highest-traffic site for getting D questions answered.
* [D on Stack Overflow](https://stackoverflow.com/questions/tagged/d) - Less traffic than the forums but possibly easier to search.
* [D on Rosetta Code](https://rosettacode.org/wiki/Category:D) - Examples of how to do many basic things in D.
* [D on Discord](https://discord.com/invite/bMZk9Q4) - Another very active community for D discussions and questions.

## People

*The people that made D the language it is.*

* [Walter Bright](https://www.walterbright.com/) - Father of D. Walter Bright is the creator and first implementer of the D programming language and has implemented compilers for several other languages.
* [Andrei Alexandrescu, PhD](http://erdani.org/) - C++ guru. Author of *The D Programming Language* and *Modern C++ Design*. With Walter Bright, Andrei co-designed many important features of D and authored a large part of D's standard library. Andrei works as a trainer in advanced C++ programming and algorithms and is now actively evangelizing D in the organization.
* [Átila Neves](https://atilaoncode.blog/) - [Deputy Leader of D](https://dlang.org/blog/2019/10/15/my-vision-of-ds-future/).
* **YOU** - Please add your information if you've done something interesting in D. It is you, the awesome people that make D awesome.

## Events

* [DConf](https://dconf.org/) - The premier event where D luminaries exchange knowledge, insight, and inspiration on everything related to the D language and its ecosystem.
* [Beerconf](https://wiki.dlang.org/Beerconf) - A casual, monthly virtual meetup for D community members.

## Organizations

*Organizations that contribute to D projects.*

* [Circular Studios](https://github.com/Circular-Studios) - We are a group of game developers at Rochester Institute of Technology building games and game tech. Hosts [Dash](https://github.com/Circular-Studios/Dash) ⭐ 428 | 🐛 33 | 🌐 D | 📅 2020-12-18, a 3D game engine written in D, and other related libs.
* [Symmetry Investments](https://symmetryinvestments.com/) - Symmetry Investments LP is an investment management company with approximately US$4.7 billion in assets under management as of 31 December 2018. Main sponsor of the [Symmetry Autumn of Code](https://dlang.org/blog/symmetry-autumn-of-code/). Have sponsored the development of [excel-d](https://dlang.org/blog/2017/05/31/project-highlight-excel-d/), [dpp](https://github.com/atilaneves/dpp) ⭐ 241 | 🐛 86 | 🌐 D | 📅 2024-06-11, [autowrap](https://github.com/symmetryinvestments/autowrap) ⭐ 82 | 🐛 51 | 🌐 D | 📅 2024-06-27, [mir-algorithm](https://github.com/libmir/mir-algorithm) ⭐ 178 | 🐛 27 | 🌐 D | 📅 2026-02-04, and various other projects.
* [D Programming Language](https://github.com/dlang) - Official Organization, hosts DMD, Phobos and other official tools and libs.
* [LDC Developers](https://github.com/ldc-developers) - LDC releated projects.
* [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including OpenGL and other multimedia/game related library bindings. (OpenGL 3, Bgfx, ENet, SDL 2, GLFW 3，OpenGLES, Free Image, Assimp3, libtheora, libogg, libvorbis, SFML 2, libpq, PhysicsFS, Open Dynamics Engine, Lua, DevIL, OpenAL, ALURE).
* [DlangScience](https://github.com/DlangScience) - A focal point and first port of call for scientific libraries and tooling for D.
* [EMSI](https://github.com/economicmodeling) - A Career building company that uses D as their main language. Hosts their opensource projects.
* [infognition](http://www.infognition.com/company.html) - Infognition is a self-funded and self-sustained company specializing in video processing and compression technologies for end-users and developers. They provide several opensource video related applications & tools written in D, hosted on [bitbucket](https://bitbucket.org/infognition/workspace/repositories/). They are also porting their main product--[Video Enchanser](http://www.infognition.com/VideoEnhancer/) from C/C++ to D.
* [libmir](https://github.com/libmir) - D's numeric library development team
* [sociomantic labs](https://github.com/sociomantic-tsunami) - Berlin based company specializing in real-time bidding for online advertising. Main sponsor of the [annual D language conference](https://dconf.org/). Has open-sourced large parts of their codebase as part of the [tsunami](https://github.com/sociomantic-tsunami) organization.
* [HuntLabs](https://github.com/huntlabs) - A technology group using DLang. Have pure D language implementation of quickly develop server-side applications and build distributed system services.

## Books

*D related books.* You can find another list of books on the [Books](https://wiki.dlang.org/Books) D wiki page.

* [TDPL](https://www.amazon.com/The-Programming-Language-Andrei-Alexandrescu/dp/0321635361/) - *The D Programming Language* by Andrei Alexandrescu.
* [Programming in D](https://ddili.org/ders/d.en/index.html) - A very detailed book about programming in D by Ali Çehreli covering many areas of the language. Has a free online version and is suitable for beginners.
* [D Cookbook](https://www.packtpub.com/en-us/product/d-cookbook-9781783287215) - A recipe-packed reference guide filled with practical tasks that are concisely explained to develop and broaden the user's abilities with the D programming language. by Adam D. Ruppe. Here is an interesting [review of the book](https://www.cppstories.com/2014/08/review-of-d-cookbook/).
* [Learning D](https://www.packtpub.com/en-us/product/learning-d-9781783552481) - This book is intended for those with some background in a C-family language who want to learn how to apply their knowledge and experience to D. (...) This book will help you get up to speed with the language and avoid common pitfalls that arise when translating C-family experience to D.
* [D Web Development](https://www.packtpub.com/en-us/product/d-web-development-9781785288890) - Whether you are new to the world of D, or already have developed applications in D, or if you want to leverage the power of D for web development, then this book is ideal for you.

## Tutorials

*D related tutorials.*

* [D Template Tutorial](https://github.com/PhilippeSigaud/D-templates-tutorial) ⭐ 233 | 🐛 11 | 🌐 HTML | 📅 2021-09-21 - A tutorial dedicated to D Templates. Very good explanation about templates. Has pdf version. by Philippe Sigaud.
* [OpenGL tutorials](https://github.com/drewet/opengl-tutorials) ⭐ 0 | 🐛 0 | 🌐 D | 📅 2014-12-30 - OpenGL tutorials in D.
* [The Dlang Tour](https://tour.dlang.org/) - An interactive tutorial for D, inspired by Golang Tour.
* [Programming in Dlang](https://www.youtube.com/watch?v=HS7X9ERdjM4\&list=PLvv0ScY6vfd9Fso-3cB4CGnSlW0E4btJV\&ab_channel=MikeShah) - An introductory video series about programming in D.
* [Pragmatic D tutorial](https://qznc.github.io/d-tut/index.html) - This is a pragmatic introduction to the D Programming Language. by Andreas Zwinkau.
* [Component programming with ranges](https://wiki.dlang.org/Component_programming_with_ranges) - A detailed blog post about how to do component programming in a idiomatic D way with ranges, with a full working example.
* [Functional image processing in D](https://blog.cy.md/2014/03/21/functional-image-processing-in-d/) - A very interesting tutorial about writing an image processing lib in D. Shows the power of D's templates/CTFE/Ranges/UFCS for functional style programming.
* [Creating a simple JSON serialiser in D](https://bradley.chatha.dev/BlogPost/JsonSerialiser/0) - D metaprogramming tutorial series
* [Let's learn D programming Game Dev!](https://www.youtube.com/watch?v=j-Zm1zgSxMQ\&list=PLgM-lc_kSqFQPF0UXgmFZpZalqcrSofe-\&ab_channel=KiRill) - A video series on learning game development with D from Ki Rill. [His channel](https://www.youtube.com/@rillki-dev/) also posts other videos related to D programming.
* [DLang YouTube Tutorials from Mike Shah](https://www.youtube.com/playlist?list=PLvv0ScY6vfd9Fso-3cB4CGnSlW0E4btJV) - Series of tutorials covering basic to advanced features of the D programming language and standard library.

## Blogs

*D related blogs.*

* [blog.dlang.org](https://dlang.org/blog/) - Official blog.
* [/r/d\_language on Reddit](https://www.reddit.com/r/d_language/) - A feed of news and blog posts about D.
* [This week in D](https://dpldocs.info/this-week-in-d/Blog.html) - A weekly overview of activity in the D community and brief advice columns to help you get the most out of the D Programming Language.
* [Planet D](http://planet.dsource.org) - A repository of co-authored D-specific blogs maintained by Vladimir Panteleev.
* [D Idioms](https://p0nce.github.io/d-idioms/) - A great blog for many useful idioms with D programming.
* [GTK-D coding](https://web.archive.org/web/20241201013031/https://gtkdcoding.com/) - Simple examples of how to use GtkD to build GUI applications.
* [Tasty D](https://tastyminerals.github.io/tasty-blog/) - A blog about learning the D programming language and various D language trivia.

## Articles

*D related Articles.*

* [Origins of the D programming language](https://dl.acm.org/doi/pdf/10.1145/3386323) - By Walter Bright, Andrei Alexandrescu, Michael Parker. The history and development of D language.
* [Purity in D](https://klickverbot.at/blog/2012/05/purity-in-d/) - An article that explains the design principles behind D's purity feature.
* [Hidden treasures in the D standard library](https://web.archive.org/web/20171119072212/http://nomad.so/2014/08/hidden-treasure-in-the-d-standard-library/) - An article talking about several useful functions and templates in Phobos.
* [D is for Data Science](https://tech.nextroll.com/blog/data/2014/11/17/d-is-for-data-science.html) - A great post about how D is suitable for data science, particularly, replacing the role of python scripts for fast prototyping.
* [D Functional Garden](https://garden.dlang.io/)

## Package Management

*Libraries for package and dependency management.*

* [code.dlang.org](https://code.dlang.org/) - Official D library repository. Backed by dub.
* [dub](https://github.com/dlang/dub) ⭐ 718 | 🐛 527 | 🌐 D | 📅 2026-01-13 - Official package and build management system for D.

## Compilers

*Official compilers for the D language.*

* [DMD](https://github.com/dlang/dmd) ⭐ 3,221 | 🐛 3,829 | 🌐 D | 📅 2026-02-11 - The reference compiler for the D programming language. Stable, builds insanely fast, very good for learning and rapid prototyping/development. Currently the frontend is implemented in D, and shared between dmd, ldc and gdc, the backend is implemented in C++.
* [LDC](https://github.com/ldc-developers/ldc) ⭐ 1,315 | 🐛 573 | 🌐 D | 📅 2026-02-11 - The LLVM-based D compiler. Uses the DMD frontend and LLVM backend. Builds slower than dmd, but generates more optimized code than DMD. It supports all the target platforms of LLVM.
* [GDC](https://github.com/D-Programming-GDC/GDC) ⚠️ Archived - GNU D Compiler. Use DMD frontend and GCC backend. Currently targets the most platforms due to the use of GCC. Generated code runs faster than DMD in most cases, on par with LDC. In the process of integration with the official GCC toolchain.

## Alternative / WIP Compilers

*These compilers may differ from or be incompatible with the official set of tools.*

* [SDC](https://github.com/snazzy-d/SDC) ⭐ 267 | 🐛 95 | 🌐 D | 📅 2026-01-05 - The Snazzy D Compiler. Written in D. Grows Smarter every day.
* [OpenD](https://opendlang.org/index.html) - A fork of the D language focused on practical and incremental improvements.

## Dev Tools

*Tools for more productive D development.*

* [D-Scanner](https://github.com/dlang-community/D-Scanner) ⭐ 251 | 🐛 128 | 🌐 D | 📅 2025-12-27 - Swiss-army knife for D source code (linting, static analysis, D code parsing, etc.)
* [dfmt](https://github.com/dlang-community/dfmt) ⭐ 212 | 🐛 103 | 🌐 D | 📅 2025-10-09 - formatter for D source code

## Build Tools

*Manage projects and compile software from source code.*

* [dub](https://github.com/dlang/dub) ⭐ 718 | 🐛 527 | 🌐 D | 📅 2026-01-13 - De facto official package and build management system for D. Will be included officially soon.
* [reggae](https://github.com/atilaneves/reggae) ⭐ 186 | 🐛 33 | 🌐 D | 📅 2026-01-15 - meta build system in D
* [cmake-d](https://github.com/dcarp/cmake-d) ⭐ 66 | 🐛 4 | 🌐 CMake | 📅 2023-06-09 - CMake D Projects
* [cook2](https://github.com/gecko0307/Cook2) ⚠️ Archived - Fast incremental build tool intended for projects in D
* [Makefile](https://github.com/bioinfornatics/MakefileForD) ⭐ 20 | 🐛 0 | 🌐 CSS | 📅 2016-04-19 - Makefile template for D projects
* [wild](https://github.com/Vild/Wild) ⭐ 6 | 🐛 2 | 🌐 D | 📅 2016-08-14 - Wild build system, used to build the [PowerNex](https://github.com/PowerNex/PowerNex) ⭐ 504 | 🐛 14 | 🌐 D | 📅 2019-03-02 kernel
* [premake](https://github.com/premake/premake-dlang) ⚠️ Archived - Premake has built-in support for D projects
* [wox](https://github.com/redthing1/wox) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2023-05-18 - A highly flexible recipe build system inspired by Make
* [scons-d](https://scons.org/) - Scons has built-in support for building D projects, thanks to Russel Winder.
* [button](https://jasonwhite.io/button/) - A universal build system to build your software at the push of a button.
* [XMake](https://xmake.io) - XMake is a crossplatform build system, that incorporated the D language and also has support for DUB repositories.

## IDEs & Editors

*Integrated Development Environment.*

* [DCD](https://github.com/dlang-community/DCD) ⭐ 360 | 🐛 61 | 🌐 D | 📅 2025-12-26 - Independent auto-complete program for the D programming language. Could be used with editors like vim, emacs, sublime text, textadept, and zeus. See [editors support](https://github.com/dlang-community/DCD/wiki/IDEs-and-Editors-with-DCD-support) ⭐ 360 | 🐛 61 | 🌐 D | 📅 2025-12-26.
* [Visual D](https://github.com/dlang/visuald) ⭐ 301 | 🐛 44 | 🌐 D | 📅 2025-10-19 - Visual Studio extension for the D programming language.
* [serve-d](https://github.com/Pure-D/serve-d) ⭐ 255 | 🐛 156 | 🌐 D | 📅 2025-12-30 - Language Server Protocol (LSP) implementation for D. Adds modern IDE features to any editor with LSP support (VSCode, Atom, Vim/Neovim and others)
* [Dutyl](https://github.com/idanarye/vim-dutyl) ⭐ 79 | 🐛 10 | 🌐 Vim script | 📅 2020-04-02 - Vim plugin that integrates various D development tools
* [IntelliJ D Language](https://intellij-dlanguage.github.io/) - Support for the D programming language within IntelliJ IDEA.
* [Dexed](https://gitlab.com/basile.b/dexed) - IDE for the D programming language, its compilers, tools and libraries.
* [code-d](https://marketplace.visualstudio.com/items?itemName=webfreak.code-d) <sup>\[[open-vsx](https://open-vsx.org/extension/webfreak/code-d)]</sup> - Visual Studio Code extension using serve-d
* [ide-d](https://packages.pulsar-edit.dev/packages/ide-d) - Pulsar (fork of Atom) extension for D using serve-d

## Lexers, Parsers & Generators

* [Pegged](https://github.com/dlang-community/Pegged) ⭐ 546 | 🐛 67 | 🌐 D | 📅 2025-07-31 - A Parsing Expression Grammar (PEG) module written in D.
* [libdparse](https://github.com/dlang-community/libdparse) ⭐ 121 | 🐛 31 | 🌐 D | 📅 2025-12-26 - A D language lexer and parser, (possibly) future standard D parser/lexer.
* [ctpg](https://github.com/youxkei/ctpg) ⭐ 45 | 🐛 0 | 🌐 D | 📅 2015-05-06 - Compile-Time Parser (with converter) Generator written in D.
* [Mono-D's DParser](https://github.com/aBothe/D_Parser) ⭐ 30 | 🐛 20 | 🌐 C# | 📅 2020-06-04 - A D parser written in C# and used in Mono-D.
* [Martin Nowak's Lexer](https://github.com/MartinNowak/lexer) ⭐ 14 | 🐛 1 | 🌐 D | 📅 2014-05-18 - A lexer generator.
* [dunnart](https://github.com/pwil3058/dunnart) ⭐ 14 | 🐛 0 | 🌐 D | 📅 2017-07-14 - LALR(1) Parser Generator written in D.
* [Goldie](https://bitbucket.org/Abscissa/goldie/wiki/Home) - Goldie Parsing System.

## Preprocesors

* [warp](https://github.com/facebookarchive/warp) ⚠️ Archived - A fast preprocessor for C and C++ used in Facebook infrastructure. Written by Walter Bright.

## Version Managers

* [dvm](https://github.com/jacob-carlborg/dvm) ⭐ 59 | 🐛 24 | 🌐 D | 📅 2025-05-08 - A small tool to install and manage DMD (self-hosting) compiler.
* [ldcup](https://github.com/kassane/ldcup) ⭐ 2 | 🐛 1 | 🌐 D | 📅 2025-12-15 - A small tool to install and manage LDC2 (LLVM backend) compiler.

## GitHub Actions

* [setup-dlang](https://github.com/dlang-community/setup-dlang) ⭐ 50 | 🐛 14 | 🌐 TypeScript | 📅 2025-10-05 - Install D compilers & DUB inside GitHub Actions
* [dub-upgrade](https://github.com/WebFreak001/dub-upgrade) ⭐ 1 | 🐛 6 | 🌐 JavaScript | 📅 2023-07-11 - Run `dub upgrade` trying to repeat on network failure and using package cache on GitHub Actions

## Testing Frameworks

* [unit-threaded](https://github.com/atilaneves/unit-threaded) ⭐ 121 | 🐛 2 | 🌐 D | 📅 2025-11-14 - Multi-threaded unit test framework
* [fluent-asserts](https://github.com/gedaiu/fluent-asserts) ⭐ 47 | 🐛 0 | 🌐 D | 📅 2026-02-02 - Fluent assertion framework with expressive syntax and detailed error messages.
* [silly](https://gitlab.com/AntonMeep/silly) - Better test runner for the D programming language. No nonsense.

## Programming Languages

*Programming languages written in D.*

* [higgs](https://github.com/higgsjs/Higgs) ⭐ 883 | 🐛 16 | 🌐 JavaScript | 📅 2023-06-09 - Higgs JavaScript Virtual Machine, implemented in D.

## Operating Systems

*Operating systems written in D.*

* [PowerNex](https://github.com/PowerNex/PowerNex) ⭐ 504 | 🐛 14 | 🌐 D | 📅 2019-03-02 - A kernel written in D
* [Trinix](https://github.com/Rikarin/Trinix) ⚠️ Archived - Hybrid operating system for x64 PC written in D
* [XOmB](https://github.com/xomboverlord/xomb) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-12-30 - An exokernel operating system written in D
* [SerpentOS](https://gitlab.com/serpent-os) - Snek factory

## Bare Metal / Kernel Development

* [D Bare bones](https://wiki.osdev.org/D_Bare_Bones) - kernel hello world in D (using GDC compiler)
* [D barebone with ldc2](https://wiki.osdev.org/D_barebone_with_ldc2) - another kernel hello world in D (using LDC compiler)
* [XOmB bare bones](https://web.archive.org/web/20161214232759/http://wiki.xomb.org/index.php?title=XOmB_Bare_Bones) - an exokernel operating system written in D. [Main page](https://web.archive.org/web/20161201061242/http://wiki.xomb.org/index.php?title=Main_Page), [github](https://github.com/xomboverlord/xomb/tree/unborn) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-12-30.
* [Bare Metal ARM Cortex-M GDC Cross Compiler](https://wiki.dlang.org/Bare_Metal_ARM_Cortex-M_GDC_Cross_Compiler) - building a bare metal ARM Cortex-M (arm-none-eabi) GDC cross compiler for a Linux host.

## General Containers

*Data structures and container libraries.*

* [dlib.container](https://github.com/gecko0307/dlib) ⭐ 225 | 🐛 4 | 🌐 D | 📅 2026-01-01 - generic data structures (GC-free dynamic and associative arrays and more)
* [EMSI containers](https://github.com/dlang-community/containers) ⭐ 111 | 🐛 14 | 🌐 D | 📅 2023-11-15 - Containers that do not use the GC
* [memutils](https://github.com/etcimon/memutils) ⭐ 45 | 🐛 3 | 🌐 D | 📅 2025-03-14 - Overhead allocators, allocator-aware containers and lifetime management for D objects
* [std.rcstring](https://github.com/burner/std.rcstring) ⭐ 9 | 🐛 0 | 🌐 D | 📅 2019-09-12 - A reference counted string implementation for D's build in string construct

## Core Utilities

*General-purpose utility libraries.*

* [NuMem](https://github.com/Inochi2D/numem) ⭐ 34 | 🐛 0 | 🌐 D | 📅 2026-01-28 - No-GC memory management utilities for DLang.
* [Joka](https://github.com/Kapendev/joka) ⭐ 19 | 🐛 0 | 🌐 D | 📅 2026-02-08 - A nogc utility library.
* [NuLib](https://github.com/Inochi2D/nulib) ⭐ 10 | 🐛 0 | 🌐 D | 📅 2026-01-28 - D "standard" library built ontop of numem.

## Web Frameworks

*Networking libraries.*

* [dlang-requests](https://github.com/ikod/dlang-requests) ⭐ 159 | 🐛 9 | 🌐 D | 📅 2025-09-16 - HTTP client library inspired by python-requests
* [libasync](https://github.com/etcimon/libasync) ⭐ 149 | 🐛 5 | 🌐 D | 📅 2024-07-04 - Cross-platform event loop library of asynchronous objects
* [serverino](https://github.com/trikko/serverino) ⭐ 74 | 🐛 1 | 🌐 D | 📅 2026-02-01 - Small and ready-to-go http server, in D
* [Handy-Httpd](https://github.com/andrewlalis/handy-httpd) ⭐ 36 | 🐛 4 | 🌐 D | 📅 2025-05-30 - A simple, lightweight, and well-documented HTTP server that lets you bootstrap ideas and have something up and running in minutes.
* [libhttp2](https://github.com/etcimon/libhttp2) ⭐ 36 | 🐛 2 | 🌐 D | 📅 2023-03-02 - HTTP/2 library in D, translated from nghttp2

*Full stack web frameworks.*

* [arsd](https://github.com/adamdruppe/arsd) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 - Adam D. Ruppe's web framework.
* [cmsed](https://github.com/rikkimax/Cmsed) ⭐ 19 | 🐛 0 | 🌐 D | 📅 2015-01-23 - A component library for Vibe that functions as a CMS.
* [vibe.d](https://vibed.org/) - Asynchronous I/O Web Framework that doesn’t get in your way, written in D.

*RPC libraries.*

* [Apache Thrift](https://code.dlang.org/packages/apache-thrift) - A lightweight, language-independent, featureful RPC framework. Thrift provides clean abstractions for data transport, data serialization, code generation, and application level processing. [Apache Thrift Page](https://thrift.apache.org/)
* [Hprose](https://github.com/hprose/hprose-d) ⭐ 26 | 🐛 1 | 🌐 D | 📅 2016-11-14 - A very newbility RPC Library for D, and it support 25+ languages now.

*Static Site Generator.*

* [DSSG](https://github.com/kambrium/dssg) ⭐ 21 | 🐛 0 | 🌐 D | 📅 2023-03-12 - A static site generator with a different approach.

## Data Serialization

*JSON, XML, protobuf and other data serialization libraries.*

* [cerealed](https://github.com/atilaneves/cerealed) ⭐ 92 | 🐛 5 | 🌐 D | 📅 2023-06-02 - Serialisation library for D
* [dproto](https://github.com/msoucy/dproto) ⭐ 38 | 🐛 26 | 🌐 D | 📅 2020-05-02 - Google Protocol Buffer support in D.

*JSON libraries.*

* [fast.json](https://github.com/etcimon/fast) ⭐ 111 | 🐛 8 | 🌐 D | 📅 2023-03-03 - A library for D that aims to provide the fastest possible implementation of some every day routines.
* [std.data.json](https://github.com/dlang-community/std_data_json) ⭐ 26 | 🐛 15 | 🌐 D | 📅 2025-12-29 - Phobos candidate for JSON serialization (based on Vibed)
* [painlessjson](https://github.com/BlackEdder/painlessjson) ⭐ 24 | 🐛 6 | 🌐 D | 📅 2019-07-12 - Convert between D types and std.json.
* [asdf](https://github.com/libmir/asdf) ⭐ 23 | 🐛 6 | 🌐 D | 📅 2025-11-06 - Cache oriented string based JSON representation for fast read & writes and serialisation.
* [vibe.data.json](https://vibed.org/api/vibe.data.json/) - JSON functions in Vibe.d. Currently the best implementation I used.
* [std.json](https://dlang.org/phobos/std_json.html) - D's standard library JSON module. Needs refinement.

*XML libraries.*

* arsd [dom.d](https://github.com/adamdruppe/arsd/blob/master/dom.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 - an xml/html DOM based on what Javascript provides in browsers
* [orange](https://github.com/jacob-carlborg/orange) ⭐ 72 | 🐛 19 | 🌐 D | 📅 2020-03-21 - General purpose serializer (currently only supports XML)
* [std.experimental.xml](https://github.com/lodo1995/experimental.xml) ⭐ 20 | 🐛 19 | 🌐 D | 📅 2017-07-27 - Phobos candidate for a XML serialization
* [newxml](https://github.com/ZILtoid1991/newxml) ⚠️ Archived - Successor of std.experimental.xml. DOM compatible, and also has a SAX parser.

## Database Clients

*Clients and bindings to C clients for relational and nosql databases.*

* [vibe.d](https://github.com/vibe-d/vibe.d) ⭐ 1,199 | 🐛 442 | 🌐 D | 📅 2025-12-17 - Vibe.d has internal support for Redis and MongoDB, which are very stable. Soon, the database drivers will be separated into independent projects.
* [arsd](https://github.com/adamdruppe/arsd) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 - Adam D. Ruppe's library; in addition to a Web backend, it also has support for database access with database.d, sqlite.d, mysql.d and postgres.d.
* [hibernated](https://github.com/buggins/hibernated) ⭐ 84 | 🐛 21 | 🌐 D | 📅 2024-12-22 - HibernateD is an ORM for D (similar to [Hibernate](https://hibernate.org/)).
* [mysql-native](https://github.com/mysql-d/mysql-native) ⭐ 82 | 🐛 41 | 🌐 D | 📅 2024-01-10 - A MySQL client implemented in native D.
* [ddbc](https://github.com/buggins/ddbc) ⭐ 80 | 🐛 15 | 🌐 D | 📅 2025-08-26 - DDBC is a DB Connector for D language (similar to JDBC). HibernateD (see below) uses ddbc for database abstraction.
* [ddb](https://github.com/pszturmaj/ddb) ⭐ 39 | 🐛 15 | 🌐 D | 📅 2022-07-31 - Database access for D2. Currently only supports PostgreSQL.
* [dvorm](https://github.com/rikkimax/Dvorm) ⭐ 17 | 🐛 0 | 🌐 D | 📅 2016-05-12 - An ORM for D with Vibe support. Works with vibe.d and mysql-d, giving it the ability to access MongoDB and MySQL.
* [libpb](https://github.com/Hax-io/libpb) ⭐ 6 | 🐛 7 | 🌐 D | 📅 2023-06-18 - Interact with a PocketBase database
* [Tiny Redis](http://adilbaig.github.io/Tiny-Redis/) - Redis driver for D. Fast, Simple, Stable. Has no dependencies.

## CLI Libraries

* [d-colorize](https://code.dlang.org/packages/colorize) - A port of the ruby library [colorize](https://github.com/fazibear/colorize) ⭐ 1,283 | 🐛 5 | 🌐 Ruby | 📅 2024-05-21. It add some methods to set color, background color and text effect on console easier using ANSI escape sequences.
* [terminal.d](https://github.com/adamdruppe/arsd/blob/master/terminal.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 - Part of Adam Ruppe's [arsd](https://github.com/adamdruppe/arsd) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 library supporting cursor and color manipulation on the console.
* [scriptlike](https://github.com/Abscissa/scriptlike) ⭐ 94 | 🐛 16 | 🌐 D | 📅 2021-03-10 - Utility library to aid writing script-like programs in D.
* [luneta](https://github.com/fbeline/luneta) ⭐ 63 | 🐛 0 | 🌐 D | 📅 2023-08-14 - A command-line fuzzy finder.
* [commandr](https://github.com/robik/commandr) ⭐ 45 | 🐛 3 | 🌐 D | 📅 2024-08-21 - A modern, powerful command line argument parser.
* [argsd](https://github.com/burner/argsd) ⭐ 18 | 🐛 0 | 🌐 D | 📅 2025-11-21 - A command line and config file parser for DLang
* [Argon](https://github.com/markuslaker/Argon) ⭐ 17 | 🐛 2 | 🌐 D | 📅 2017-11-10 - A processor for command-line arguments, an alternative to Getopt, written in D.
* [dexpect](https://github.com/grogancolin/dexpect/) ⭐ 14 | 🐛 3 | 🌐 D | 📅 2020-12-21 - A D implementation of the expect framework. Handy for bash emulation.
* [gogga](https://github.com/deavmi/gogga) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2026-01-04 - simple easy-to-use colorful logger for command-line applications
* [argparse](https://code.dlang.org/packages/argparse) - Flexible parser of command line arguments.

## CLI Applications

* [onedrive](https://github.com/abraunegg/onedrive) ⭐ 12,073 | 🐛 8 | 🌐 D | 📅 2026-02-11 - #1 Free OneDrive Client for Linux.
* [Literate](https://github.com/zyedidia/Literate) ⭐ 896 | 🐛 36 | 🌐 D | 📅 2022-07-10 - A literate programming tool for any language.
* [tshare](https://github.com/trikko/tshare) ⭐ 137 | 🐛 0 | 🌐 D | 📅 2023-12-13 - Fast file sharing from cli, using transfer.sh.
* [Soulfind](https://github.com/soulfind-dev/soulfind) ⭐ 40 | 🐛 7 | 🌐 D | 📅 2026-02-08 - Soulseek server implementation in D.
* [todod](https://github.com/BlackEdder/todod) ⭐ 17 | 🐛 2 | 🌐 D | 📅 2017-03-22 - Todod is a command line based todo list manager. It also has support for shell interaction based on [linenoise](https://github.com/antirez/linenoise) ⭐ 4,185 | 🐛 145 | 🌐 C | 📅 2026-01-10.

## GUI Libraries

*Libraries for working with graphical user interface applications.*

* [DLangUI](https://github.com/buggins/dlangui) ⭐ 858 | 🐛 98 | 🌐 D | 📅 2025-12-21 - Cross Platform GUI for D programming language. My personal favorite, because it is written in D(not a binding), and is cross platform. DLangUI also has a good showcase in the IDE [DLangIDE](https://github.com/buggins/dlangide) ⭐ 486 | 🐛 126 | 🌐 D | 📅 2024-03-12.
* [minigui](https://arsd-official.dpldocs.info/arsd.minigui.html) - A smallish GUI widget library, aiming to be on par with at least HTML4 forms and a few other expected gui components. It's part of the [arsd libraries](https://github.com/adamdruppe/arsd/blob/master/minigui.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07.
* [GtkD](https://github.com/gtkd-developers/GtkD) ⭐ 328 | 🐛 56 | 🌐 D | 📅 2025-11-01 - GtkD is a D binding and OO wrapper of GTK+. GtkD is actively maintained and is currently the most stable GUI lib for D.
* [tkD](https://github.com/nomad-software/tkd) ⭐ 119 | 🐛 6 | 🌐 D | 📅 2021-10-15 - GUI toolkit for the D programming language based on Tcl/Tk.
* [dqml](https://github.com/filcuc/dqml) ⭐ 42 | 🐛 3 | 🌐 D | 📅 2022-10-12 - Qt Qml bindings for the D programming language.
* [Sciter-Dport](https://github.com/sciter-sdk/Sciter-Dport) ⭐ 34 | 🐛 0 | 🌐 D | 📅 2017-06-12 - D bindings for the [Sciter](https://sciter.com) - crossplatform HTML/CSS/script desktop UI toolkit.
* [giD](https://github.com/Kymorphia/gid) ⭐ 33 | 🐛 3 | 🌐 D | 📅 2026-01-30 - GObject Introspection D Package Repository.
* [microui-d](https://github.com/Kapendev/microui-d) ⭐ 12 | 🐛 0 | 🌐 D | 📅 2025-08-27 - A tiny immediate-mode UI library.
* [Fluid](https://git.samerion.com/Samerion/Fluid) - A declarative cross-platform user interface library for D.

*Note*: You can also find a list of GUI libs on [wiki.dlang.org](https://wiki.dlang.org/Libraries_and_Frameworks#GUI_Libraries), but not all of the libraries are actively maintained now.

## GUI Applications

* [tilix](https://github.com/gnunn1/tilix) ⭐ 5,620 | 🐛 445 | 🌐 D | 📅 2026-01-20 - A tiling terminal emulator for Linux using GTK+ 3.
* [Inochi Creator](https://github.com/Inochi2D/inochi-creator) ⭐ 1,088 | 🐛 133 | 🌐 D | 📅 2025-06-16 - Inochi2D Rigging Application.
* [Inochi Session](https://github.com/Inochi2D/inochi-session) ⭐ 375 | 🐛 23 | 🌐 D | 📅 2025-11-08 - Application that allows streaming with Inochi2D puppets.

## Game Bindings

*Bindings to game development related libraries in C, C++, and other languages.*

* [Godot-D](https://github.com/godot-d/godot-d) ⭐ 210 | 🐛 33 | 🌐 D | 📅 2023-09-04 - D language bindings for the Godot Engine's GDNative API.
* [DSFML](https://github.com/Jebbs/DSFML) ⭐ 97 | 🐛 49 | 🌐 D | 📅 2019-04-28 - A static binding of SFML in a way that makes sense for D.
* [raylib-d](https://github.com/schveiguy/raylib-d) ⭐ 80 | 🐛 10 | 🌐 D | 📅 2025-10-06 - D bindings for raylib.
* [DAllegro5](https://github.com/SiegeLord/DAllegro5) ⭐ 45 | 🐛 6 | 🌐 D | 📅 2024-10-31 - D binding/wrapper to Allegro 5, a modern game programming library.
* [BindBC](https://github.com/BindBC) - Bindings compatible with `-betterC` and `@nogc`, using [bindbc-loader](https://github.com/BindBC/bindbc-loader) ⭐ 26 | 🐛 0 | 🌐 D | 📅 2025-01-28.
  * [SDL 2](https://github.com/BindBC/bindbc-sdl) ⭐ 124 | 🐛 1 | 🌐 D | 📅 2026-02-07 - Multimedia library
  * [Nuklear](https://github.com/Timu5/bindbc-nuklear) ⭐ 45 | 🐛 1 | 🌐 D | 📅 2023-09-22 - Immediate mode GUI
  * [OpenGL](https://github.com/BindBC/bindbc-opengl) ⭐ 42 | 🐛 0 | 🌐 D | 📅 2024-10-19 - Graphics API
  * [GLFW 3](https://github.com/BindBC/bindbc-glfw) ⭐ 42 | 🐛 0 | 🌐 D | 📅 2026-01-02 - Window/Input library
  * [WebGPU](https://github.com/DLangGamedev/bindbc-wgpu) ⭐ 32 | 🐛 1 | 🌐 C++ | 📅 2025-12-01 - Modern GPU API
  * [Imgui](https://github.com/Inochi2D/i2d-imgui) ⭐ 23 | 🐛 7 | 🌐 D | 📅 2025-10-22 - Immediate mode GUI
  * [bgfx](https://github.com/GoaLitiuM/bindbc-bgfx) ⭐ 21 | 🐛 1 | 🌐 D | 📅 2022-12-17 - Cross-Platform renderer
  * [FreeType](https://github.com/BindBC/bindbc-freetype) ⭐ 19 | 🐛 0 | 🌐 D | 📅 2025-12-14 - Font rendering
  * [Lua](https://github.com/BindBC/bindbc-lua) ⭐ 18 | 🐛 2 | 🌐 D | 📅 2024-03-02 - Scripting language
  * [raylib3](https://github.com/o3o/bindbc-raylib3) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2023-12-24 - Game library
  * [SFML 2](https://github.com/BindBC/bindbc-sfml) ⭐ 12 | 🐛 2 | 🌐 D | 📅 2024-11-28 - Multimedia library
  * [OpenAL](https://github.com/BindBC/bindbc-openal) ⭐ 9 | 🐛 1 | 🌐 D | 📅 2024-01-18 - Audio library
  * [SoLoud](https://github.com/DLangGamedev/bindbc-soloud) ⭐ 9 | 🐛 0 | 🌐 D | 📅 2025-04-13 - Audio library
  * [Newton Dynamics](https://github.com/DLangGamedev/bindbc-newton) ⭐ 9 | 🐛 0 | 🌐 D | 📅 2025-03-29 - Physics library
  * [FreeImage](https://github.com/BindBC/bindbc-freeimage) ⭐ 6 | 🐛 0 | 🌐 D | 📅 2023-07-07 - Image loading
  * [Blend2D](https://github.com/kdmult/bindbc-blend2d) ⭐ 5 | 🐛 0 | 🌐 D | 📅 2023-04-05 - Vector graphics
  * [KiWi](https://github.com/aferust/bindbc-kiwi) ⭐ 4 | 🐛 0 | 🌐 D | 📅 2019-10-25 - UI widget toolkit
  * [NanoVG](https://github.com/aferust/bindbc-nanovg) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2020-04-20 - Vector graphics
  * [Zstandard](https://github.com/ZILtoid1991/bindbc-zstandard) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2019-05-07 - Fast compression
  * [JoyShockLibrary](https://github.com/ZILtoid1991/bindbc-JSL) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2020-10-01 - Gamepad/Gyro input
  * [HarfBuzz](https://github.com/DlangGraphicsWG/bindbc-harfbuzz) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2024-11-19 - Text shaping
  * [SDL2\_gfx](https://github.com/aferust/bindbc-sdlgfx) ⭐ 1 | 🐛 0 | 🌐 D | 📅 2019-11-19 - Drawing primitives for SDL2
  * [nanomsg-next-gen](https://github.com/darkridder/bindbc-nng) ⭐ 1 | 🐛 0 | 🌐 D | 📅 2020-10-03 - Messaging library
* [sokol-d](https://github.com/floooh/sokol-d) ⭐ 23 | 🐛 3 | 🌐 C | 📅 2026-02-08 - D bindings for the sokol headers.
* [DerelictOrg](https://github.com/DerelictOrg) - Bindings, now largely outdated. BindBC is its modern successor.
  * [ENet](https://github.com/DerelictOrg/DerelictENet) ⭐ 8 | 🐛 2 | 🌐 D | 📅 2020-09-08 - Networking library
  * [libpq](https://github.com/DerelictOrg/DerelictPQ) ⭐ 8 | 🐛 0 | 🌐 D | 📅 2025-09-08 - PostgreSQL library
  * [Open Dynamics Engine (ODE)](https://github.com/DerelictOrg/DerelictODE) ⭐ 7 | 🐛 1 | 🌐 D | 📅 2017-06-16 - Physics library
  * [libogg](https://github.com/DerelictOrg/DerelictOgg) ⭐ 5 | 🐛 0 | 🌐 D | 📅 2017-06-04 - Audio codec
  * [OpenGLES](https://github.com/DerelictOrg/DerelictGLES) ⭐ 4 | 🐛 6 | 🌐 D | 📅 2017-02-12 - Graphics API
  * [PhysicsFS](https://github.com/DerelictOrg/DerelictPHYSFS) ⭐ 4 | 🐛 0 | 🌐 D | 📅 2017-09-22 - Virtual file system
  * [libvorbis](https://github.com/DerelictOrg/DerelictVorbis) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2017-08-12 - Audio codec
  * [ALURE](https://github.com/DerelictOrg/DerelictALURE) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2017-06-04 - Audio library
  * [libtheora](https://github.com/DerelictOrg/DerelictTheora) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2017-06-04 - Video codec
  * [DevIL](https://github.com/DerelictOrg/DerelictIL) ⭐ 0 | 🐛 0 | 🌐 D | 📅 2017-11-15 - Image library

## Game Libraries

*D libraries for game development.*

* [InMath](https://github.com/Inochi2D/inmath) ⭐ 10 | 🐛 0 | 🌐 D | 📅 2025-10-15 - Games math library for D.
* [godot-math](https://github.com/AuburnSounds/godot-math) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2026-01-06 - A D port of Godot's linear algebra with unchanged semantics.
* [text-mode](https://github.com/AuburnSounds/text-mode) ⭐ 3 | 🐛 2 | 🌐 D | 📅 2026-01-22 - Virtual text mode with 8x8 Unicode font and markup language.

*Libraries for 2D-related projects.*

* [HipremeEngine](https://github.com/MrcSnm/HipremeEngine) ⭐ 134 | 🐛 4 | 🌐 D | 📅 2026-02-10 - Cross Platform D-Lang Game Engine with scripting support.
* [PixelPerfectEngine](https://github.com/ZILtoid1991/pixelperfectengine) ⚠️ Archived - 2D graphics engine written in D.
* [Parin](https://github.com/Kapendev/parin) ⭐ 56 | 🐛 2 | 🌐 D | 📅 2026-02-08 - A delightfully simple 2D game engine.
* [gfm](https://github.com/drug007/gfm7) ⭐ 4 | 🐛 0 | 🌐 D | 📅 2024-07-27 - D gamedev toolkit.

*Libraries for 2D/3D-related projects.*

* [rengfx](https://github.com/bmchtech/rengfx) ⭐ 87 | 🐛 1 | 🌐 D | 📅 2024-10-12 - lightweight, expressive, extensible 2D/3D game engine.

*Libraries for 3D-related projects.*

* [Dagon](https://github.com/gecko0307/dagon) ⭐ 385 | 🐛 11 | 🌐 D | 📅 2026-02-08 - 3D game engine for D. See: <https://gecko0307.github.io/dagon/>
* [Voxelman](https://github.com/MrSmith33/voxelman) ⭐ 129 | 🐛 3 | 🌐 D | 📅 2022-05-10 - Plugin-based client-server voxel game engine written in D language.

## Games

*Games made with D.*

* [Electronvolt (formerly Atrium)](https://github.com/gecko0307/electronvolt) ⭐ 115 | 🐛 1 | 🌐 D | 📅 2025-09-08 - FPS game with physics based puzzles using OpenGL.
* [Backgammony](https://github.com/jonathanballs/backgammony) ⭐ 40 | 🐛 2 | 🌐 D | 📅 2024-06-19 - A Backgammon GUI for Linux built with Gtk.
* [Spacecraft](https://github.com/Ingrater/Spacecraft) ⭐ 18 | 🐛 1 | 🌐 D | 📅 2014-06-11 - A 3d multiplayer deathmatch space game written in D 2.0.
* [Dtanks](https://github.com/kingsleyh/dtanks) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2016-01-28 - Robot Tank Battle Game.
* [Worms Within](https://kapendev.itch.io/worms-within) - A bite-sized escape room game.
* [Clean & Haunted](https://kapendev.itch.io/clean-haunted) - Clean a spooky haunted house.
* [Runani](https://kapendev.itch.io/runani) - An endless runner game where you help cute animals.
* [A Short Metamorphosis](https://kapendev.itch.io/a-short-metamorphosis) - A cute visual novel about looking at an egg.

## Internationalization

* [bindbc-icu](https://github.com/shoo/bindbc-icu) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2025-03-11 - bindbc bindings for the unicode ICU library.

## Image Processing

* [color.d](https://github.com/adamdruppe/arsd/blob/master/color.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 + [bmp.d](https://github.com/adamdruppe/arsd/blob/master/bmp.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07, [jpg.d](https://github.com/adamdruppe/arsd/blob/master/jpg.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07, [png.d](https://github.com/adamdruppe/arsd/blob/master/png.d) ⭐ 549 | 🐛 54 | 🌐 D | 📅 2026-02-07 - basic color struct, HSL functions and reading and writing image files
* [dlib.image](https://github.com/gecko0307/dlib) ⭐ 225 | 🐛 4 | 🌐 D | 📅 2026-01-01 - image processing (8 and 16 bits per channel, floating point operations, filtering, FFT, HDRI, graphics formats support including JPEG and PNG)
* [ArmageddonEngine](https://github.com/CyberShadow/ae/tree/master/utils/graphics) ⭐ 177 | 🐛 13 | 🌐 D | 📅 2026-02-09 - Vladimir Panteleev's ae library has a package for image processing in functional style, which is described in the article [Functional Image Processing in D](https://blog.cy.md/2014/03/21/functional-image-processing-in-d/).
* [opencvd](https://github.com/aferust/opencvd) ⭐ 23 | 🐛 1 | 🌐 D | 📅 2021-09-06 - Unofficial OpenCV binding for D

## Machine Learning

* [vectorflow](https://github.com/Netflix/vectorflow) ⭐ 1,298 | 🐛 15 | 🌐 D | 📅 2024-05-02 - Nexflix's opensource deep learning framework.
* [tfd](https://github.com/ShigekiKarita/tfd) ⭐ 33 | 🐛 0 | 🌐 D | 📅 2021-06-15 - Tensorflow wrapper for D
* [bindbc-onnxruntime](https://github.com/lempiji/bindbc-onnxruntime) ⭐ 11 | 🐛 0 | 🌐 D | 📅 2023-03-05 - bindbc bindings to Microsoft's cross-platform, high performance ML inferencing and training accelerator
* [grain2](https://github.com/ShigekiKarita/grain2) ⭐ 8 | 🐛 0 | 🌐 D | 📅 2020-03-14 - Autograd and GPGPU library for dynamic neural networks in D

## Parallel Computing

* [DCompute](https://github.com/libmir/dcompute) ⭐ 139 | 🐛 17 | 🌐 D | 📅 2026-02-07 - [GPGPU with Native D for OpenCL and CUDA](https://dlang.org/blog/2017/07/17/dcompute-gpgpu-with-native-d-for-opencl-and-cuda/)
* [DerelictCUDA](https://github.com/DerelictOrg/DerelictCUDA) ⭐ 17 | 🐛 0 | 🌐 D | 📅 2019-02-22 - Dynamic bindings to the CUDA library for the D Programming Language.
* [DerelictCL](https://github.com/DerelictOrg/DerelictCL) ⭐ 7 | 🐛 0 | 🌐 D | 📅 2019-10-30 - Dynamic bindings to the OpenCL library for the D Programming Language.

## Scientific

*Scientific programming.*

* [mir](https://github.com/libmir/mir) ⭐ 211 | 🐛 0 | 🌐 D | 📅 2022-06-05 - Sandbox for some mir packages: sparse tensors, Hoffman and others.
* [mir-algorithm](https://github.com/libmir/mir) ⭐ 211 | 🐛 0 | 🌐 D | 📅 2022-06-05 - N-dimensional arrays (matrixes, tensors), algorithms, general purpose library.
* [scid](https://github.com/DlangScience/scid) ⭐ 92 | 🐛 8 | 🌐 D | 📅 2020-04-30 - Scientific library for the D programming language
* [mir-random](https://github.com/libmir/mir-random) ⭐ 32 | 🐛 2 | 🌐 D | 📅 2024-12-17 - Advanced Random Number Generators.
* [dstats](https://github.com/DlangScience/dstats) ⭐ 26 | 🐛 7 | 🌐 D | 📅 2022-12-10 - A statistics library for D.

### Language Processing

* [bindbc-mecab](https://github.com/lempiji/bindbc-mecab) ⭐ 1 | 🐛 0 | 🌐 D | 📅 2020-07-24 - bindbc MeCab binding (Part-of-Speech and Morphological Analyzer for Japanese)

## Text Processing

* [eBay's TSV utilities](https://github.com/eBay/tsv-utils/) ⭐ 1,475 | 🐛 24 | 🌐 D | 📅 2022-09-14 - Filtering, statistics, sampling, joins and other operations on TSV files. Very fast, especially good for large datasets.
* [hunt-markdown](https://github.com/huntlabs/hunt-markdown) ⭐ 14 | 🐛 1 | 🌐 D | 📅 2022-04-15 - A markdown parsing and rendering library for D programming language. Support commonMark.

## Logging

*Print with care.*

* [dlogg](https://github.com/NCrashed/dlogg) ⭐ 12 | 🐛 2 | 🌐 D | 📅 2017-11-10 - Logging for concurrent applications and daemons with lazy and delayed logging, logrotate support.
* [dlog](https://github.com/deavmi/dlog) ⭐ 1 | 🐛 2 | 🌐 D | 📅 2025-03-21 - extensible logging framework with message transformation support and custom loggers and contexts
* [std.experimenatal.logger](https://dlang.org/phobos/std_experimental_logger.html) - Phobos's upcoming standard logging facility.

## Configuration

*Parsing configuration files.*

* [D:YAML](https://github.com/dlang-community/D-YAML) ⭐ 123 | 🐛 21 | 🌐 D | 📅 2026-01-24 - YAML parser and emitter for the D programming language.
* [sdlang](https://github.com/dlang-community/SDLang-D) ⭐ 119 | 🐛 34 | 🌐 D | 📅 2023-04-30 - An SDL (Simple Declarative Language) library for D.
* [inifile-D](https://github.com/burner/inifiled) ⭐ 22 | 🐛 0 | 🌐 D | 📅 2022-10-19 - A compile time ini file parser and writter generator for D

## Blog Engine

*Hosting blogs yourself.*

* [mood](https://github.com/mihails-strasuns/mood) ⭐ 44 | 🐛 6 | 🌐 D | 📅 2020-11-20 - simple vibe.d based blog engine

## Dependency Injection

*Apply inversion of control.*

* [Poodinis](https://github.com/mbierlee/poodinis) ⭐ 73 | 🐛 2 | 🌐 D | 📅 2026-01-08 - A dependency injection framework for D with support for autowiring.

## Cryptography

* [Botan](https://github.com/etcimon/botan) ⭐ 92 | 🐛 6 | 🌐 D | 📅 2025-12-20 - Block & stream ciphers, public key crypto, hashing, KDF, MAC, PKCS, TLS, ASN.1, BER/DER, etc.
* [OpenSSL](https://github.com/D-Programming-Deimos/openssl) ⭐ 48 | 🐛 10 | 🌐 C | 📅 2025-08-26 - D version of the C headers for OpenSSL.
* [Crypto](https://github.com/shove70/crypto) ⭐ 33 | 🐛 1 | 🌐 D | 📅 2025-01-01 - A D Library of encryption, decryption, encode, hash, and message digital signatures.

## Unmaintained

*Old or archived projects saved for reference.*

* [Hunt Framework](https://github.com/huntlabs/hunt-framework/) ⭐ 309 | 🐛 22 | 🌐 D | 📅 2024-03-11 - Hunt is a high-level D Programming Language Web framework that encourages rapid development and clean, pragmatic design. It lets you build high-performance Web applications quickly and easily.
* [DWT](https://github.com/d-widget-toolkit/dwt) ⭐ 141 | 🐛 15 | 🌐 D | 📅 2023-09-19 - A library for creating cross-platform GUI applications. GWT is a port of the Java SWT library to D. DWT was promoted as a semi-standard GUI library for D, but unfortunately didn't catch up popularity yet.
* [hunt](https://github.com/huntlabs/hunt) ⭐ 98 | 🐛 15 | 🌐 D | 📅 2024-01-17 - A refined core library for D programming language. The module has concurrency / collection / event / io / logging / text / serialize and more.
* [dunit](https://github.com/nomad-software/dunit) ⚠️ Archived - Advanced unit testing & mocking toolkit
* [collie](https://github.com/huntlabs/collie) ⭐ 60 | 🐛 3 | 🌐 D | 📅 2018-09-12 - An asynchronous event-driven network framework written in dlang, like netty framework in D.
* [hunt-entity](https://github.com/huntlabs/hunt-entity) ⭐ 58 | 🐛 7 | 🌐 D | 📅 2022-07-22 - Hunt entity is an object-relational mapping tool for the D programming language. Referring to the design idea of JPA, support PostgreSQL / MySQL / SQLite.
* [hunt-database](https://github.com/huntlabs/hunt-database) ⭐ 49 | 🐛 21 | 🌐 D | 📅 2023-11-15 - Hunt database abstraction layer for D programing language, support PostgreSQL / MySQL / SQLite.
* [grpc](https://github.com/huntlabs/grpc-dlang) ⭐ 43 | 🐛 11 | 🌐 D | 📅 2022-03-12 - Grpc for D programming language, hunt-http library based.
* [kissrpc](https://github.com/huntlabs/kissrpc) ⭐ 41 | 🐛 0 | 🌐 D | 📅 2018-03-22 - Fast and light, flatbuffers based rpc framework.
* [LibUI](https://github.com/Extrawurst/DerelictLibui) ⭐ 34 | 🐛 4 | 🌐 D | 📅 2021-05-28 - Dynamic Binding for [libui](https://github.com/andlabs/libui) ⭐ 10,859 | 🐛 249 | 🌐 C | 📅 2024-05-29
* [hunt-http](https://github.com/huntlabs/hunt-http) ⭐ 31 | 🐛 4 | 🌐 D | 📅 2022-05-17 - HTTP/1 and HTTP/2 protocol library for D.
* [hunt-net](https://github.com/huntlabs/hunt-net) ⭐ 20 | 🐛 3 | 🌐 D | 📅 2022-02-21 - High-performance network library for D programming language, event-driven asynchonous implemention(IOCP / kqueue / epoll).
* [flatbuffers](https://github.com/huntlabs/flatbuffers) ⭐ 10 | 🐛 1 | 🌐 D | 📅 2017-07-21 - D Programming Language implementation of the google flatbuffers library.
* [hunt-cache](https://github.com/huntlabs/hunt-cache) ⭐ 6 | 🐛 1 | 🌐 D | 📅 2022-12-26 - D language universal cache library, using radix, redis and memcached.
* [hunt-console](https://github.com/huntlabs/hunt-console) ⭐ 4 | 🐛 1 | 🌐 D | 📅 2021-10-29 - Hunt console creation easier to create powerful command-line applications.
* [hunt-validation](https://github.com/huntlabs/hunt-validation) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2024-01-18 - A data validation library for DLang based on hunt library.
* [hunt-time](https://github.com/huntlabs/hunt-time) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2021-03-17 - A time library and similar to Joda-time and Java.time api.
* [hunt-gossip](https://github.com/huntlabs/hunt-gossip) ⭐ 0 | 🐛 1 | 🌐 D | 📅 2019-03-11 - A Apache V2 gossip protocol implementation for D programming language.
