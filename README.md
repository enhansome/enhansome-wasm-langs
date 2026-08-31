# Awesome WebAssembly Languages with stars

WebAssembly, or wasm for short, is a low-level bytecode format that runs in the browser just like JavaScript.
It is designed to be faster to parse than JavaScript, as well as faster to execute which makes it a suitable compilation target for new and existing languages.

This repo contains a list of languages that currently compile to or have their VMs in WebAssembly(wasm)  :octocat:

## Contents

* :chicken: - In Production.
  * [C](#c)
  * [C++](#cpp)
  * [Rust](#rust)
  * [Go](#go)

* :hatched\_chick: - Stable for production usage.
  * [.Net](#dotnet)
  * [AssemblyScript](#assemblyscript)
  * [Brainfuck](#brainfuck)
  * [C#](#csharp)
  * [Clean](#clean)
  * [Cyber](#cyber)
  * [COBOL](#cobol)
  * [Dart](#dart)
  * [F#](#fsharp)
  * [Forth](#forth)
  * [Grain](#grain)
  * [LabVIEW](#labview)
  * [Lobster](#lobster)
  * [Lox](#lox)
  * [Lua](#lua)
  * [Nelua](#nelua)
  * [Never](#never)
  * [Rego](#rego)</br>
  * [TypeScript](#typescript)
  * [Uxn](#uxn)
  * [WebAssembly](#webassembly)
  * [Zig](#zig)</br>

* :hatching\_chick: - Unstable but usable.
  * [Ada](#ada)
  * [Berry](#berry)
  * [C4wa](#c4wa)
  * [Coi](#coi)
  * [Crystal](#crystal)
  * [D](#d)
  * [Eclair](#eclair)
  * [Eel](#eel)
  * [Elixir](#elixir)
  * [Janet](#janet)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [KCL](#kcl)
  * [Kotlin/Wasm](#kotlin)
  * [Lisp](#lisp)
  * [Lys](#lys)
  * [Pascal](#pascal)
  * [Perl](#perl)
  * [PHP](#php)
  * [Poetry](#poetry)
  * [Python](#python)
  * [Prolog](#prolog)
  * [R](#r)
  * [Rebol](#rebol)
  * [Ring](#ring)
  * [Ruby](#ruby)</br>
  * [Scheme](#scheme)
  * [Swift](#swift)
  * [Tcl](#tcl)
  * [V](#v)
  * [Virgil](#virgil)
  * [Wa](#wa)
  * [Wonkey](#wonkey)

* :egg: - Work in progress.
  * [Ballerina](#ballerina)
  * [BASIC](#basic)
  * [Co](#co)
  * [Faust](#faust)
  * [Forest](#forest)
  * [Haskell](#haskell)
  * [Julia](#julia)
  * [Kou](#kou)
  * [MoonBit](#moonbit)
  * [Nerd](#nerd)
  * [Nim](#nim)
  * [Ocaml](#ocaml)
  * [Plorth](#plorth)
  * [Roc](#roc)
  * [Theta](#theta)
  * [Wase](#wase)
  * [xcc](#xcc)</br>

* :skull\_and\_crossbones: - Unmaintained or Deprecated
  * ~~[Astro](#astro)~~ `Unmaintained`
  * ~~[Idris](#idris)~~ `Unmaintained`
  * ~~[Speedy.js](#speedyjs)~~ `Unmaintained`
  * ~~[Turboscript](#turboscript)~~ `Unmaintained`
  * ~~[Wah](#wah)~~ `Unmaintained`
  * ~~[Walt](#walt)~~ `Unmaintained`
  * ~~[Wam](#wam)~~ `Unmaintained`
  * ~~[Wracket](#wracket)~~ `Unmaintained`

***

### <a name="dotnet"></a>.Net <sup>[top⇈](#contents)</sup>

> .NET Framework is a software framework developed by Microsoft that runs primarily on Microsoft Windows. It includes a large class library named Framework Class Library (FCL) and provides language interoperability (each language can use code written in other languages) across several programming languages.

* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) - a web UI framework using C#/Razor and HTML, running client-side via WebAssembly. Source is maintained on [ASP.Net Core](https://github.com/dotnet/aspnetcore) ⭐ 38,408 | 🐛 4,143 | 🌐 C# | 📅 2026-08-31 repo.
* [Mono](https://github.com/mono/mono/tree/master/sdks/wasm) ⭐ 11,467 | 🐛 2,266 | 🌐 C# | 📅 2024-08-27 - an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime. For a real-work example, see this repository which contains the [Windows 10 calculator](https://github.com/nventive/calculator) ⭐ 415 | 🐛 61 | 🌐 C# | 📅 2025-08-26. The application is built using standard C++ 11 and C++/CX, with a calculation engine that dates back from 1995. Made by possible with mono via [Uno Platform](https://platform.uno/a-piece-of-windows-10-is-now-running-on-webassembly-natively-on-ios-and-android/).
* [NativeAOT-LLVM](https://github.com/dotnet/runtimelab/tree/feature/NativeAOT-LLVM) ⭐ 1,616 | 🐛 257 | 📅 2026-08-31 - an experimental fork of the CoreCLR .NET runtime that compiles .NET applications into single-file executables, with the primary target being WASM
* [Bolero](https://fsbolero.io/) - Bolero brings Blazor to F# developers with an easy to use Model-View-Update architecture, HTML combinators, hot reloaded templates, type-safe endpoints, advanced routing and remoting capabilities, and more.

***

### <a name="ada"></a>Ada <sup>[top⇈](#contents)</sup>

> Ada is a structured, statically typed, imperative, and object-oriented high-level programming language, inspired by Pascal and other languages. It has built-in language support for design by contract (DbC), extremely strong typing, explicit concurrency, tasks, synchronous message passing, protected objects, and non-determinism. Ada improves code safety and maintainability by using the compiler to find errors in favor of runtime errors.

* [adawebpack](https://github.com/godunko/adawebpack) ⭐ 83 | 🐛 4 | 🌐 Ada | 📅 2025-02-16 - GNAT-LLVM compiler for WebAssembly target, GNAT Run Time Library and AdaWebPack bindings for Web API.
* [adagl](https://github.com/godunko/adagl) ⭐ 11 | 🐛 0 | 🌐 Ada | 📅 2024-12-28 - Multiplatform Ada/OpenGL bindings (ported to native/OpenGL, A2JS/WebGL and WASM/WebGL).
* [adawebui](https://github.com/godunko/adawebui) ⭐ 3 | 🐛 1 | 🌐 Ada | 📅 2022-06-05 - GUI based on adawebpack.\\

***

### <a name="assemblyscript"></a>AssemblyScript <sup>[top⇈](#contents)</sup>

> AssemblyScript is a new compiler targeting WebAssembly while utilizing TypeScript's syntax and node's vibrant ecosystem. Instead of requiring complex toolchains to set up, you can simply npm install it - or run it in a browser.

* [AssemblyScript](https://github.com/AssemblyScript/assemblyscript) ⭐ 17,995 | 🐛 201 | 🌐 WebAssembly | 📅 2026-07-22 - main repository.

***

### <a name="astro"></a>Astro <sup>[top⇈](#contents)</sup>

> Astro is a fun safe language for rapid prototyping and high performance applications.

* ~~[Astro](https://github.com/astrolang/astro) ⭐ 804 | 🐛 7 | 🌐 Rust | 📅 2023-08-10 - main repository.~~ `Unmaintained`

***

### <a name="ballerina"></a>Ballerina <sup>[top⇈](#contents)</sup>

> Ballerina is an open-source programming language for the cloud that makes it easier to use, combine, and create network services.
> The WebAssembly compiler is implemented for the native Ballerina compiler [nBallerina](https://github.com/ballerina-platform/nballerina) ⭐ 144 | 🐛 88 | 🌐 Ballerina | 📅 2024-10-23.

* [Main repository](https://github.com/ballerina-platform/nballerina/tree/wasm) ⭐ 144 | 🐛 88 | 🌐 Ballerina | 📅 2024-10-23 - Ballerina-to-wasm compiler

***

### <a name="basic"></a>BASIC <sup>[top⇈](#contents)</sup>

> BASIC (acronym for "Beginners' All-purpose Symbolic Instruction Code") is an early general-purpose and high-level programming language. It's still one of the simplest and easy to learn languages.

* [EndBASIC](https://github.com/endbasic/endbasic) ⭐ 384 | 🐛 31 | 🌐 Rust | 📅 2026-08-31 - BASIC environment with a REPL, a web interface, a graphical console, and RPi support written in Rust. You can try it out [here](https://repl.endbasic.dev/).
* [gobasic](https://github.com/skx/gobasic) ⚠️ Archived - a BASIC interpreter written in Golang.
* [basic\_rs](https://github.com/yiransheng/basic_rs) ⭐ 41 | 🐛 4 | 🌐 Rust | 📅 2019-01-17 - a BASIC Interpreter/Compiler for the Original Dartmouth Version written in Rust. Also provides `basic2wasm` tool which compiles BASIC to WebAssembly using binaryen.
* [basicwasm](https://github.com/navionguy/basicwasm) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2026-03-14 - a GWBasic interpreter compiled to WASM with a Web UI.

***

### <a name="berry"></a>Berry <sup>[top⇈](#contents)</sup>

> Berry is an ultra-lightweight dynamically typed embedded scripting language. It's designed for lower-performance embedded devices, fast, multi-paradigm, simple, flexible, and has very small RAM footprint.

* [berry](https://github.com/berry-lang/berry) ⭐ 1,055 | 🐛 11 | 🌐 C | 📅 2026-08-26 - main repo.
* [berry\_web](https://github.com/berry-lang/berry_web/) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2025-09-26 - Berry web playground. The project contains port of the Berry to Emscripten platform.

***

### <a name="brainfuck"></a>Brainfuck <sup>[top⇈](#contents)</sup>

> Brainfuck is an esoteric programming language created in 1993 by Urban Müller, and notable for its extreme minimalism.
> The language consists of only eight simple commands and an instruction pointer. While it is fully Turing-complete, it is not intended for practical use, but to challenge and amuse programmers.

* [Brainfuck Wa-lang](https://github.com/wa-lang/wa/tree/master/waroot/examples/brainfuck) ⭐ 1,767 | 🐛 6 | 🌐 Go | 📅 2026-04-30 - a Brainfuck interpreter written in [凹语言/Wa-lang](https://github.com/wa-lang/wa) ⭐ 1,767 | 🐛 6 | 🌐 Go | 📅 2026-04-30 and compiled to WebAssembly.
* [Brainfuck2Wasm](https://github.com/verdie-g/brainfuck2wasm) ⭐ 47 | 🐛 1 | 🌐 JavaScript | 📅 2022-02-27 - a Brainfuck-to-wasm compiler and playground.
* [bfwasm](https://github.com/surma/bfwasm) ⭐ 28 | 🐛 1 | 🌐 JavaScript | 📅 2019-10-04 - A non-optimizing Brainf\_ck to WebAssembly compiler with WASI support.
* [BrainfuckWebassembly](https://github.com/serprex/brainwebfuckassembly) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-29 - a simple Brainfuck-to-wasm compiler in one function.
* [BrainfuckRsWasm](https://github.com/shritesh/brainfuck-rs-wasm) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2017-12-04 - a Brainfuck interpreter written in Rust and compiled to WebAssembly.

***

### <a name="c"></a>C <sup>[top⇈](#contents)</sup>

> C is a general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
> C was originally developed by Dennis Ritchie between 1969 and 1973 at Bell Labs,\[6] and used to re-implement the Unix operating system.

* [Emscripten](https://github.com/kripken/emscripten) ⭐ 27,586 | 🐛 2,481 | 🌐 C++ | 📅 2026-08-31 - an LLVM-to-JavaScript/Webassembly compiler. It takes LLVM bitcode - which can be generated from C/C++, using llvm-gcc (DragonEgg) or clang, or any other language that can be converted into LLVM - and compiles that into JavaScript or wasm.
* [Cheerp](https://github.com/leaningtech/cheerp-meta) ⭐ 1,190 | 🐛 5 | 🌐 JavaScript | 📅 2025-09-24 - an open-source, enterprise-grade C/C++ compiler for Web applications. Cheerp can compile virtually any C/C++ code to WebAssembly and/or JavaScript.

***

### <a name="csharp"></a>C# <sup>[top⇈](#contents)</sup>

> C# is a multi-paradigm programming language encompassing strong typing, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines.
> Its development team is led by Anders Hejlsberg.
> WebAssembly support is achieved through [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor).

* See [.Net](#dotnet)

***

### <a name="cpp"></a>C++ <sup>[top⇈](#contents)</sup>

> C++ is a general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
> It was designed with a bias toward system programming and embedded, resource-constrained and large systems, with performance, efficiency and flexibility of use as its design highlights.
> The development of the language was started in 1979 by Bjarne Stroustrup as a "C with Classes".

* See [C](#c).

***

### <a name="c4wa"></a>c4wa <sup>[top⇈](#contents)</sup>

> C4wa ("C for Web Assembly") is a subset of Standard C specifically targeted for simple and efficient Web Assembly compilation.
> Generated WASM files include no overhead, out of the box compatible with any Web Assembly runtime, support import of variable-argument
> functions (such as `printf`). There is also an option to create well-formatted and readable WAT files.

* [c4wa](https://github.com/kign/c4wa) ⭐ 110 | 🐛 3 | 🌐 WebAssembly | 📅 2022-01-29 - main repository.

***

### <a name="clean"></a>Clean <sup>[top⇈](#contents)</sup>

> Clean is a general purpose, state-of-the-art, pure and lazy functional programming language designed for making real-world applications.
> Some of its most notable language features are uniqueness typing, dynamic typing, and generic functions.

* [ABC interpreter](https://gitlab.com/clean-and-itasks/abc-interpreter) - interpreter for Clean's intermediate language ABC, with a WebAssembly version.
* [iTasks](https://gitlab.com/clean-and-itasks/itasks-sdk) - integration of the above ABC interpreter with browser applications.

***

### <a name="co"></a>Co <sup>[top⇈](#contents)</sup>

> A programming language similar to Go and TypeScript.

* [Co](https://github.com/rsms/co) ⭐ 151 | 🐛 1 | 🌐 TypeScript | 📅 2020-03-13 - main repository

***

### <a name="cobol"></a>COBOL <sup>[top⇈](#contents)</sup>

> COBOL is a compiled English-like programming language designed for business use.
> It is imperative, procedural, and object-oriented. COBOL is primarily used in business, finance, and administrative systems.

* [Cobaul](https://github.com/cloudflare/cobaul) ⭐ 400 | 🐛 4 | 🌐 COBOL | 📅 2026-04-23 - toolchain used to [support COBOL in CloudFlare workers](https://blog.cloudflare.com/cloudflare-workers-now-support-cobol/)

***

### <a name="coi"></a>Coi <sup>[top⇈](#contents)</sup>

> Coi is a component-based language for high-performance web apps (Fast, Minimal, Type-safe) with the following features:
>
> * Fine-Grained Reactivity: State changes map directly to DOM elements at compile-time. No Virtual DOM overhead.
> * Type-Safe Components: Compile-time error checking with strictly typed parameters and state.
> * Minimal Runtime: Tiny WASM binaries with high-performance updates for DOM, Canvas, and more.
> * Integrated DOM & Styling: Write HTML elements and scoped CSS directly in components.
> * View Control Flow: Declarative `<if>`, `<else>`, and `<for>` tags for conditional rendering and iteration.

* [Coi](https://github.com/io-eric/coi) ⭐ 570 | 🐛 2 | 🌐 C++ | 📅 2026-08-17 - main repository.

***

### <a name="crystal"></a>Crystal <sup>[top⇈](#contents)</sup>

> Crystal is a programming language with the following goals:
>
> * Have a syntax similar to Ruby (but compatibility with it is not a goal)
> * Statically type-checked but without having to specify the type of variables or method arguments.
> * Be able to call C code by writing bindings to it in Crystal.
> * Have compile-time evaluation and generation of code, to avoid boilerplate code.
> * Compile to efficient native code.

* [Crystal](https://github.com/crystal-lang/crystal) ⭐ 20,391 | 🐛 2,040 | 🌐 Crystal | 📅 2026-08-31 - main repository
* [POC PR](https://github.com/crystal-lang/crystal/pull/10870) ⭐ 20,391 | 🐛 2,040 | 🌐 Crystal | 📅 2026-08-31 - PR adding initial support for WebAssembly

***

### <a name="cyber"></a>Cyber <sup>[top⇈](#contents)</sup>

> Fast, efficient, and concurrent scripting. Dynamic and gradual types; Concurrency with fibers; Multithreaded; Memory safe; FFI and Embeddable.

* [Cyber](https://github.com/fubark/cyber) ⭐ 1,520 | 🐛 37 | 🌐 Zig | 📅 2025-12-21 - project repository

***

### <a name="d"></a>D <sup>[top⇈](#contents)</sup>

> D is a general-purpose programming language with static typing, systems-level access, and C-like syntax.

* [LDC](https://github.com/ldc-developers/ldc) ⭐ 1,367 | 🐛 580 | 🌐 D | 📅 2026-08-31 - LLVM-based D compiler, which can generate WASM since version 1.11.0.

***

### <a name="dart"></a>Dart <sup>[top⇈](#contents)</sup>

> An approachable, portable, and productive language for high-quality apps on any platform

* [sdk](https://github.com/dart-lang/sdk) ⭐ 11,267 | 🐛 8,436 | 🌐 Dart | 📅 2026-08-31 - The Dart SDK, including the VM, dart2js, core libraries, and more.
* [language](https://github.com/dart-lang/language) ⭐ 2,933 | 🐛 1,326 | 🌐 TeX | 📅 2026-08-31 - Design of the Dart language
* [Use via Flutter](https://flutter.dev/wasm) - How to compile Dart to WebAssembly for a Flutter Web application

***

### <a name="eclair"></a>Eclair <sup>[top⇈](#contents)</sup>

> Eclair is a minimal, fast Datalog implementation that compiles to LLVM IR and WASM.

* [eclair-lang](https://github.com/luc-tielen/eclair-lang) ⭐ 232 | 🐛 9 | 🌐 Haskell | 📅 2024-01-22 - The Eclair compiler, which can compile Eclair code to LLVM IR and WASM.

***

### <a name="eel"></a>Eel <sup>[top⇈](#contents)</sup>

> Eel is a small language used for, among other things, writing visualizer "presets" for [Milkdrop](http://www.geisswerks.com/milkdrop/), the music visualization program which came with [Winamp](https://en.wikipedia.org/wiki/Winamp).

* [eel-wasm](https://github.com/captbaritone/eel-wasm) ⭐ 60 | 🐛 10 | 🌐 TypeScript | 📅 2025-12-16 - Compiles Milkdrop flavored Eel to Wasm in the browser. Intended to become a component of [Butterchurn](https://github.com/jberg/butterchurn) ⭐ 1,933 | 🐛 24 | 🌐 JavaScript | 📅 2026-04-20, a WebGL implementation of the Milkdrop Visualizer.

***

### <a name="elixir"></a>Elixir <sup>[top⇈](#contents)</sup>

> Elixir is a dynamic, functional language designed for building scalable and maintainable applications.
> Elixir builds on top of Erlang and shares the same abstractions for building distributed, fault-tolerant applications.

* ~~[Firefly](https://github.com/GetFirefly/firefly) ⚠️ Archived - An alternative BEAM implementation (with AOT compiler) designed for WebAssembly. \[Unmaintained]~~
* ~~[ElixirWasm](https://github.com/jamen/elixir-wasm) ⭐ 134 | 🐛 0 | 🌐 Elixir | 📅 2019-02-22 - an elixir compiler for wasm. \[Unmaintained]~~

***

### <a name="fsharp"></a>F# <sup>[top⇈](#contents)</sup>

> F# is a mature, open source, cross-platform, functional-first programming language. It empowers users and organizations to tackle complex computing problems with simple, maintainable and robust code.
> WebAssembly support is achieved through [Bolero](https://fsbolero.io/), a set of free and open-source libraries and tools built on top of [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor).
> F# was mainly conceived by Don Syme of Microsoft Research but it's now maintained by the [F# Foundation](http://foundation.fsharp.org/) and its community.

* See [.Net](#dotnet)

***

### <a name="faust"></a>Faust <sup>[top⇈](#contents)</sup>

> Faust (Functional Audio Stream) is a functional programming language specifically designed for real-time signal processing and synthesis. A distinctive characteristic of Faust is to be fully compiled.

* [Faust](https://github.com/grame-cncm/faust) ⭐ 3,142 | 🐛 242 | 🌐 C++ | 📅 2026-08-31 - main repository.

***

### <a name="forest"></a>Forest <sup>[top⇈](#contents)</sup>

> Forest is a functional programming language that compiles to WebAssembly. The main repo contains the compiler and core syntaxes, currently implemented in Haskell.

* [ForestLang](https://github.com/forest-lang/core) ⭐ 626 | 🐛 8 | 🌐 Haskell | 📅 2021-08-04 - main repository.

***

### <a name="forth"></a>Forth <sup>[top⇈](#contents)</sup>

> Forth is an interactive, extensible, imperative, untyped, stack-based programming language.

* [WAForth](https://github.com/remko/waforth) ⭐ 590 | 🐛 8 | 🌐 WebAssembly | 📅 2025-07-15 - Bootstrapping Dynamic Forth Interpreter/Compiler for & in WebAssembly.
* [WASM Forth](https://github.com/stefano/wasm-forth) ⭐ 151 | 🐛 0 | 🌐 Python | 📅 2019-05-05 - Forth implementation for wasm.

***

### <a name="go"></a>Go <sup>[top⇈](#contents)</sup>

> Go is a statically typed compiled language in the tradition of C, with memory safety, garbage collection, structural typing, and CSP-style concurrent programming features added.

* [Go](https://github.com/golang/go) ⭐ 136,852 | 🐛 10,099 | 🌐 Go | 📅 2026-08-31 - main repository.
* [TinyGo](https://github.com/aykevl/tinygo) ⭐ 17,680 | 🐛 571 | 🌐 Go | 📅 2026-08-31 - a subset of Go targeted to embedded devices and WebAssembly.

***

### <a name="grain"></a>Grain <sup>[top⇈](#contents)</sup>

> Grain is a strongly-typed functional programming language built for the modern web.

* [Grain](https://github.com/grain-lang/grain) ⭐ 3,468 | 🐛 280 | 🌐 Reason | 📅 2026-08-21 - main repository.
* [GrainWeb](https://grain-lang.org/) - Web page.

***

### <a name="haskell"></a>Haskell <sup>[top⇈](#contents)</sup>

> Haskell is a standardized, general-purpose purely functional programming language, with non-strict semantics and strong static typing. It is named after logician Haskell Curry.\[1] The latest standard of Haskell is Haskell 2010. As of May 2016, a group is working on the next version, Haskell 2020.

* ~~[Asterius](https://github.com/tweag/asterius) ⚠️ Archived - a Haskell to WebAssembly compiler. \[Unmaintained]~~
* ~~[HaskellWasm](https://github.com/haskell-wasm/wasm) ⚠️ Archived - a Haskell compiler infrastructure for generating WebAssembly. \[Unmaintained]~~
* ~~[DHC](https://github.com/dfinity/dhc) ⭐ 168 | 🐛 2 | 🌐 Haskell | 📅 2019-03-04 - a Haskell compiler that accepts only a tiny subset of the language and produces WebAssembly binaries. \[Unmaintained]~~
* [haskell-wasm](https://github.com/SPY/haskell-wasm) ⭐ 153 | 🐛 7 | 🌐 Haskell | 📅 2025-01-18 - Haskell WebAssembly Toolkit. It includes Language helpers and a fully spec-compatible WASM interpreter.
* [wasm-cross](https://github.com/WebGHC/wasm-cross) ⭐ 145 | 🐛 8 | 🌐 Nix | 📅 2020-09-26 - A toolchain for cross compiling C and Haskell to WebAssembly, using the WebGHC and LLVM.
* [GHC WASM](https://gitlab.haskell.org/haskell-wasm/ghc-wasm-meta) - GHC's wasm backend.

***

### <a name="idris"></a>Idris <sup>[top⇈](#contents)</sup>

> Idris is a general purpose pure functional programming language with dependent types. Dependent types allow types to be predicated on values, meaning that some aspects of a program’s behaviour can be specified precisely in the type. It is compiled, with eager evaluation. Its features are influenced by Haskell and ML.

* ~~[Idris-codegen-WASM](https://github.com/SPY/idris-codegen-wasm) ⭐ 81 | 🐛 1 | 🌐 Haskell | 📅 2018-06-26 - WASM codegen repository.~~ `Unmaintained`

***

### <a name="janet"></a>Janet <sup>[top⇈](#contents)</sup>

> Janet makes a good system scripting language, or a language to embed in other programs. It's like a "modern Lisp", featuring great and easy C interop and a variety of data types like arrays, structs, tables, etc.

* [Janet](https://github.com/janet-lang/janet) ⭐ 4,373 | 🐛 57 | 🌐 C | 📅 2026-08-30 - main repository. You can try it out [here](https://janet-lang.org/#Try-It).

***

### <a name="java"></a>Java <sup>[top⇈](#contents)</sup>

> Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented, and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.
> Java was originally developed by James Gosling at Sun Microsystems and released in 1995 as a core component of Sun Microsystems' Java platform. The language derives much of its syntax from C and C++, but it has fewer low-level facilities than either of them.

* [TeaVM](https://github.com/konsoletyper/teavm) ⭐ 3,100 | 🐛 189 | 🌐 Java | 📅 2026-08-26 - an ahead-of-time translating compiler (transpiler) of Java bytecode, that's capable of emitting JavaScript and WebAssembly.
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly) ⭐ 1,052 | 🐛 22 | 🌐 Java | 📅 2026-08-17 - A Java bytecode to WebAssembly compiler. It can generate the WebAssembly binary or text format. It is written in Java itself and can be integrated with other Java build tools.
* [Bytecoder](https://github.com/mirkosertic/Bytecoder) ⭐ 958 | 🐛 40 | 🌐 Java | 📅 2026-08-17 - A Rich Domain Model for Java Bytecode and Framework to interpret and transpile it to other languages such as JavaScript, OpenCL or WebAssembly.
* [CheerpJ](https://github.com/leaningtech/cheerpj-meta) ⭐ 683 | 🐛 14 | 📅 2026-06-12 - A Java compiler for the web that converts any Java client application into standard HTML5/WebAssembly/JavaScript.
* [Rise JVM](https://github.com/AmazingRise/rise-jvm) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2022-05-03 - Rise JVM is a minimal Java VM based on WASM. You can try it out [here](https://risehere.net/rise-jvm).

***

### <a name="javascript"></a>JavaScript <sup>[top⇈](#contents)</sup>

> JavaScript is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is a language that is also characterized as dynamic, weakly typed, prototype-based and multi-paradigm.

* [hermes](https://github.com/facebook/hermes) ⭐ 11,277 | 🐛 238 | 🌐 JavaScript | 📅 2026-08-28 - Hermes is a JavaScript engine optimized for fast start-up of React Native apps. It features ahead-of-time static optimization and compact bytecode. [Emscripten](https://github.com/facebook/hermes/blob/main/doc/Emscripten.md) ⭐ 11,277 | 🐛 238 | 🌐 JavaScript | 📅 2026-08-28 and [WASI](https://github.com/guest271314/hermes/blob/shermes-wasm/doc/WASI.md) ⭐ 0 | 🐛 0 | 📅 2025-02-11 support.
* [otto](https://github.com/robertkrimen/otto) ⭐ 8,449 | 🐛 50 | 🌐 Go | 📅 2025-06-13 - a JavaScript parser and interpreter written natively in Go.
* [Boa](https://github.com/boa-dev/boa) ⭐ 7,523 | 🐛 212 | 🌐 Rust | 📅 2026-08-31 - an embeddable and experimental Javascript engine written in Rust. You can try it out [here](https://boajs.dev/boa/playground/).
* [goja](https://github.com/dop251/goja) ⭐ 7,065 | 🐛 32 | 🌐 Go | 📅 2026-08-26 - an implementation of ECMAScript 5.1 in pure Go with emphasis on standard compliance and performance.
* [Duktape](https://github.com/svaarala/duktape) ⭐ 6,209 | 🐛 474 | 🌐 JavaScript | 📅 2024-03-22 - an embeddable Javascript engine, with a focus on portability and compact footprint that's capable of being run in the browser via WebAssembly.
* [Porffor](https://github.com/CanadaHonk/porffor) ⭐ 5,097 | 🐛 33 | 🌐 JavaScript | 📅 2026-08-29 - a from-scratch experimental AOT optimizing JS/TS -> Wasm/C engine/compiler/runtime. You can try it out [here](https://porffor.dev/).
* [Jint](https://github.com/sebastienros/jint) ⭐ 4,711 | 🐛 15 | 🌐 C# | 📅 2026-08-31 - an embeddable Javascript interpreter for .NET which can run on any modern .NET platform as it supports .NET Standard 2.0 and .NET 4.6.2 targets (and later).
* [Javy](https://github.com/bytecodealliance/javy) ⭐ 2,738 | 🐛 22 | 🌐 Rust | 📅 2026-08-12 - a JavaScript to WebAssembly toolchain, capable of generating WASI-compatible modules from JS by embedding the QuickJS engine.
* [quickjs-emscripten](https://github.com/justjake/quickjs-emscripten) ⭐ 1,699 | 🐛 39 | 🌐 TypeScript | 📅 2026-07-23 - Safely execute untrusted Javascript in your JS/TS, and execute synchronous code that uses async functions.
* [sebastianwessel-quickjs](https://github.com/sebastianwessel/quickjs) ⭐ 931 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-08 - a typescript package to execute JavaScript and TypeScript code in a webassembly quickjs sandbox. You can try it out [here](https://sebastianwessel.github.io/quickjs/playground.html).
* [wasmedge-quickjs](https://github.com/second-state/wasmedge-quickjs) ⭐ 562 | 🐛 63 | 🌐 JavaScript | 📅 2024-10-15 - A high-performance, secure, extensible, and OCI-complaint JavaScript runtime for WasmEdge.  Features TCP/UDP support via WasmEdge Sockets.
* [jz](https://github.com/dy/jz) ⭐ 159 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-31 - A minimal, fast AOT compiler for a functional JavaScript subset to WebAssembly.
* [SpiderMonkey](https://github.com/bytecodealliance/spidermonkey-wasm-rs) ⚠️ Archived - experimental Rust bindings and generic builtins for SpiderMonkey for building WASI-compatible modules from JavaScript.

***

### <a name="julia"></a>Julia <sup>[top⇈](#contents)</sup>

> Julia was designed from the beginning for high performance. Julia programs compile to efficient native code for multiple platforms via LLVM.

* [julia-wasm](https://github.com/Keno/julia-wasm) ⭐ 343 | 🐛 13 | 🌐 JavaScript | 📅 2021-11-08 - Emscripten & LLVM Julia to WASM compiler.
* ~~[Charlotte.jl](https://github.com/MikeInnes/Charlotte.jl) ⭐ 112 | 🐛 20 | 🌐 Julia | 📅 2022-01-27 - a Julia to WebAssembly/Javascript compiler~~ `Unmaintained`
* [WebAssemblyCompiler.jl](https://tshort.github.io/WebAssemblyCompiler.jl/stable/) - Julia to Wasm GC compiler via Binaryen

***

### <a name="kcl"></a>KCL <sup>[top⇈](#contents)</sup>

> KCL is a constraint-based record & functional language mainly used in configuration and policy scenarios.

* [KCLVM](https://github.com/KusionStack/KCLVM) ⭐ 2,407 | 🐛 28 | 🌐 Rust | 📅 2026-08-31 - LLVM-based KCL compiler, which can generate WASM.

***

### <a name="kotlin"></a>Kotlin <sup>[top⇈](#contents)</sup>

> Kotlin is a modern but already mature programming language aimed to make developers happier. It's concise, safe, interoperable with Java and other languages, and provides many ways to reuse code between multiple platforms for productive programming.
>
> Kotlin/Wasm is the new target and toolchain in the Kotlin family. It has a few special properties:
>
> * It compiles to Wasm directly without any additional layers, to compile as fast as possible, including incrementally in the future.
> * It uses experimental/fresh proposals like GC, Typed Function References, Exception Handling, and Stringref.

* [Kotlin/Wasm examples](https://github.com/Kotlin/kotlin-wasm-examples) ⭐ 586 | 🐛 25 | 🌐 HTML | 📅 2026-01-14
* [Kotlin/Wasm (Kotlin WebAssembly)](https://kotl.in/wasm)

***

### <a name="kou"></a>Kou <sup>[top⇈](#contents)</sup>

> A minimal language compiled into wasm bytecode.

* [Kou](https://github.com/utatti/kou) ⭐ 137 | 🐛 1 | 🌐 TypeScript | 📅 2019-08-26 - main repository.

***

### <a name="labview"></a>LabVIEW <sup>[top⇈](#contents)</sup>

> LabVIEW is a development environment for the G dataflow graphical programming language used for data acquisition, instrument control, and industrial automation.

* [Vireo](https://github.com/ni/vireosdk) ⭐ 50 | 🐛 51 | 🌐 C++ | 📅 2024-07-16 - An open-source runtime capable of running the virtual instrument assembly representation of the G dataflow graphical programming language created by G Web Development Software.
* [G Web Development Software](https://www.ni.com/en/shop/electronic-test-instrumentation/programming-environments-for-electronic-test-and-instrumentation/what-is-g-web-development-software.html) - A standalone development environment implementing a subset of the G dataflow graphical programming language to create web-based user interfaces for test and measurement applications.

***

### <a name="lisp"></a>Lisp <sup>[top⇈](#contents)</sup>

> Lisp (historically LISP) is a family of programming languages with a long history and a distinctive, fully parenthesized prefix notation.

* [Wisp](https://github.com/mbrock/wisp) ⭐ 305 | 🐛 15 | 🌐 JavaScript | 📅 2026-08-28 - Wisp is a Lisp system for WebAssembly and native execution.
* [Femto Emacs](https://github.com/FemtoEmacs/wasCm) ⭐ 35 | 🐛 0 | 🌐 TeX | 📅 2023-08-11 - translates Low Level Lisp into WebAssembly.

***

### <a name="lobster"></a>Lobster <sup>[top⇈](#contents)</sup>

> Lobster is a statically typed language with flow-sensitive type inference and specialization, compile time reference counting (lifetime analysis) that looks a bit like Python. It was originally intended specifically for games.
> Lobster has its own Wasm backend that compiles directly to linkable (with LLD) .wasm files.

* [Lobster github](https://github.com/aardappel/lobster) ⭐ 2,735 | 🐛 18 | 🌐 C++ | 📅 2026-08-29
* [Lobster home](http://strlen.com/lobster/).
* [Lobster docs](http://aardappel.github.io/lobster/README_FIRST.html)
* [Compile to Wasm](http://aardappel.github.io/lobster/implementation.html) - how to compile.
* [Wasm backend details](http://aardappel.github.io/lobster/implementation_wasm.html) - how it is implemented, useful for other language implementors.

***

### <a name="lox"></a>Lox <sup>[top⇈](#contents)</sup>

> Lox is a language created by Bob Nystrom, used to teach compilers in the book Crafting Interpreters. It is dynamically typed, and supports classes, closures, and first-class functions.

* [loxcraft](https://github.com/ajeetdsouza/loxcraft) ⭐ 365 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 uses WebAssembly for its [online playground](https://ajeetdsouza.github.io/loxcraft/).

***

### <a name="lua"></a>Lua <sup>[top⇈](#contents)</sup>

> Lua is a lightweight, multi-paradigm programming language designed primarily for embedded systems and clients.\[2] Lua is cross-platform, since the interpreter is written in ANSI C, and has a relatively simple C API.
> Lua was originally designed in 1993 as a language for extending software applications to meet the increasing demand for customization at the time.

* [GopherLua](https://github.com/yuin/gopher-lua) ⭐ 6,976 | 🐛 103 | 🌐 Go | 📅 2026-04-01 - a Lua5.1(+ goto statement in Lua5.2) VM and compiler written in Go. It provides Go APIs that allow you to easily embed a scripting language to your Go host programs.
* [DCLua](https://github.com/milochristiansen/lua) ⭐ 923 | 🐛 1 | 🌐 Go | 📅 2026-07-17 - a Lua 5.3 VM and compiler written in Go. It's intended to allow easy embedding into Go programs, with minimal fuss and bother.
* [WasmLua](https://github.com/vvanders/wasm_lua) ⭐ 803 | 🐛 5 | 🌐 C | 📅 2023-11-29 - a Lua VM running in the browser.
* [Wasmoon](https://github.com/ceifa/wasmoon) ⭐ 697 | 🐛 22 | 🌐 TypeScript | 📅 2026-07-29 - a high level Lua VM with JS bindings.
* [Pluto](https://github.com/PlutoLang/Pluto) ⭐ 695 | 🐛 23 | 🌐 C++ | 📅 2026-08-22 - a superset of Lua 5.4 with a focus on general-purpose programming. You can try it out [here](https://pluto-lang.org/web/).
* [Wasm2Lua](https://github.com/SwadicalRag/wasm2lua) ⭐ 221 | 🐛 15 | 🌐 WebAssembly | 📅 2021-12-14 - can compile WebAssembly modules to pure Lua (or with FFI LuaJIT for extra speed).
* [Luwa](https://github.com/serprex/luwa) ⭐ 97 | 🐛 1 | 🌐 Lua | 📅 2019-04-06 - a Lua-to-wasm JIT compiler.
* [erdian718/lua](https://github.com/erdian718/lua) ⭐ 27 | 🐛 1 | 🌐 Go | 📅 2023-09-15 (aka ofunc/lua) - a fork of DCLua, featuring IO capabilities, HTTP client, IoC, and more.
* [PlutoScript](https://github.com/PlutoLang/PlutoScript) ⭐ 11 | 🐛 4 | 🌐 JavaScript | 📅 2025-09-10 - Pluto's extension aimed for web scripting. Provides JS interop and ability to use Pluto anywhere JavaScript works.

***

### <a name="lys"></a>Lys <sup>[top⇈](#contents)</sup>

> Lys is a typed functional language that compiles directly to WebAssembly.

* [Lys](https://github.com/lys-lang/lys) ⭐ 429 | 🐛 7 | 🌐 TypeScript | 📅 2025-01-24 - main repository.

***

### <a name="moonbit"></a>MoonBit <sup>[top⇈](#contents)</sup>

> MoonBit is an end-to-end programming language toolchain for cloud and edge computing using WebAssembly. The language is like Rust with GC support. The fast compiler is optimized to produce very compact WASM binaries.

* [Core library](https://github.com/moonbitlang/core) ⭐ 1,191 | 🐛 130 | 🌐 MoonBit | 📅 2026-08-31 - open-sourced standard library. Compiler source code is not available yet.
* [MoonBit](https://www.moonbitlang.com) - main website. You can try the language out [here](https://try.moonbitlang.com/).

***

### <a name="nelua"></a>Nelua <sup>[top⇈](#contents)</sup>

> Minimal, simple, efficient, statically typed, compiled, metaprogrammable, safe, and extensible systems programming language with a Lua flavor.

* [Nelua](https://github.com/edubart/nelua-lang/) ⭐ 2,417 | 🐛 26 | 🌐 Lua | 📅 2025-06-24 - project repository
* [Nelua on the Web](https://github.com/edubart/nelua-lang/discussions/11) ⭐ 2,417 | 🐛 26 | 🌐 Lua | 📅 2025-06-24 - Nelua-wasm discussion

***

### <a name="nerd"></a>Nerd <sup>[top⇈](#contents)</sup>

> NerdLang is a substract of JS with some additions, focus on efficiency.
> Nerd is a JavaScript native compiler aiming to make JavaScript universal, Nerd is able to compile native apps for Windows, Mac, Linux, iOS, Android, Raspberry, STM32, Arduino, Web (including WASM), and more.

* [Nerd](https://github.com/NerdLang/nerd) ⭐ 3,613 | 🐛 16 | 🌐 C++ | 📅 2023-01-25 - main repository.

***

### <a name="never"></a>Never <sup>[top⇈](#contents)</sup>

> Never is a simple functional programming language. Technically it may be classified as syntactically scoped, strongly typed, call by value, functional programming language.

* [Never](https://github.com/never-lang/never) ⭐ 461 | 🐛 2 | 🌐 C | 📅 2024-05-12 - project repository
* [Never on the Web](https://never-lang.readthedocs.io/en/latest/never-web/) - Never language demo

***

### <a name="nim"></a>Nim <sup>[top⇈](#contents)</sup>

> A fringe language with some beautiful design patterns.

* [nlvm](https://github.com/arnetheduck/nlvm) ⭐ 776 | 🐛 14 | 🌐 Nim | 📅 2026-08-30 - LLVM-based compiler for Nim with a WebAssembly target supported out of the box
* [nwasm](https://github.com/stisa/nwasm) ⭐ 51 | 🐛 1 | 📅 2020-09-01 - a webassembly backend for nim.
* [Nim wasm helpers](https://github.com/Feneric/nim-wasm-helpers) ⭐ 27 | 🐛 2 | 📅 2019-01-19 - a helper to set up a VM configured to build WebAssembly code using Nim.

***

### <a name="ocaml"></a>Ocaml <sup>[top⇈](#contents)</sup>

> OCaml, originally named Objective Caml, is the main implementation of the programming language Caml, created by Xavier Leroy, Jérôme Vouillon, Damien Doligez, Didier Rémy, Ascánder Suárez and others in 1996. A member of the ML language family, OCaml extends the core Caml language with object-oriented programming constructs.

* ~~[OcamlRun](https://github.com/sebmarkbage/ocamlrun-wasm) ⭐ 257 | 🐛 1 | 🌐 Shell | 📅 2017-03-06 - a build script for compiling OCaml bytecode interpreter to wasm using emscripten \[Unmaintained]~~
* [Ocaml](https://github.com/SanderSpies/ocaml/tree/wasm/wasmcomp) ⭐ 78 | 🐛 12 | 🌐 OCaml | 📅 2020-09-01 - a fork of main repo containing work on OCaml to wasm compilation.

***

### <a name="pascal"></a>Pascal <sup>[top⇈](#contents)</sup>

> Pascal is a general purpose imperative, procedural and object-oriented
> static typing programming language. The Free Pascal compiler targets many
> processor architectures, including wasm32; operating systems, including
> WASI; and embedded platforms.

* [Free Pascal](https://wiki.freepascal.org/WebAssembly) - Free Pascal compilation target and Pascal-to-Javascript runtime.

***

### <a name="perl"></a>Perl <sup>[top⇈](#contents)</sup>

> Perl is a general-purpose programming language originally developed for text manipulation and now used for a wide range of tasks including system administration, web development, network programming, GUI development, and more.

* [WebPerl](https://github.com/haukex/webperl) ⭐ 297 | 🐛 8 | 🌐 HTML | 📅 2023-03-27 - Perl 5 in the browser.

***

### <a name="php"></a>PHP <sup>[top⇈](#contents)</sup>

> PHP is a general-purpose scripting language that is especially suited to server-side web development, in which case PHP generally runs on a web server. Any PHP code in a requested file is executed by the PHP runtime, usually to create dynamic web page content or dynamic images used on websites or elsewhere.

* [PIB](https://github.com/oraoto/pib) ⭐ 989 | 🐛 32 | 🌐 PHP | 📅 2022-12-07 - a PHP runtime in the browser.
* [WebAssembly Language Runtimes](https://github.com/vmware-labs/webassembly-language-runtimes) ⭐ 369 | 🐛 28 | 🌐 Shell | 📅 2024-06-05 - up-to-date PHP (including php-cgi) prebuilt for WASI
* [PHP WASM](https://github.com/soyuka/php-wasm) ⭐ 99 | 🐛 3 | 🌐 Dockerfile | 📅 2024-10-16 - maintained fork of PIB with PHP 8 support based on the work of [seanmorris](https://github.com/seanmorris/php-wasm) ⭐ 1,361 | 🐛 39 | 🌐 PHP | 📅 2026-08-30.

***

### <a name="plorth"></a>Plorth <sup>[top⇈](#contents)</sup>

> Plorth is stack based, concatenative, strongly typed functional scripting language which is easy to embed to applications written in C++. It's inspired by Forth and Factor programming languages.

* [Plorth](https://github.com/RauliL/plorth-webassembly) ⭐ 16 | 🐛 0 | 📅 2017-12-20 - main repository.

***

### <a name="poetry"></a>Poetry <sup>[top⇈](#contents)</sup>

> Poetry is a poetically dynamic and simple programming language that compiles to WebAssembly. It has a minimalisting syntax akin to CoffeeScript and gives you full control over wasm imports and exports.

* [Poetry](https://github.com/FantasyInternet/poetry) ⭐ 58 | 🐛 3 | 🌐 WebAssembly | 📅 2019-01-13 - main repository.

***

### <a name="python"></a>Python <sup>[top⇈](#contents)</sup>

> Python is an open source interpreted high-level programming language for general-purpose programming. Created by Guido van Rossum and first released in 1991, Python has a design philosophy that emphasizes code readability, notably using significant whitespace. It provides constructs that enable clear programming on both small and large scales.

* [RustPython](https://github.com/RustPython/RustPython) ⭐ 22,317 | 🐛 400 | 🌐 Rust | 📅 2026-08-31 - A Python 3 interpreter written in Rust. Check the demo [here](https://rustpython.github.io/demo/)
* [MicroPython](https://github.com/micropython/micropython/tree/master/ports/webassembly) ⭐ 22,033 | 🐛 1,531 | 🌐 C | 📅 2026-08-31 - a lean and efficient Python implementation for microcontrollers and constrained systems.
* [Pyodide](https://github.com/iodide-project/pyodide) ⭐ 14,808 | 🐛 396 | 🌐 Python | 📅 2026-08-27 - a port of Python to WebAssembly that includes the core packages of the scientific Python stack (Numpy, Pandas, matplotlib).  Objects transparently convert and share between Python and Javascript.
* [WebAssembly Language Runtimes](https://github.com/vmware-labs/webassembly-language-runtimes) ⭐ 369 | 🐛 28 | 🌐 Shell | 📅 2024-06-05 - up-to-date CPython prebuilt for WASI
* [micropython-wasm](https://github.com/rafi16jan/micropython-wasm) ⭐ 54 | 🐛 5 | 🌐 JavaScript | 📅 2022-11-16 - MicroPython build which features wide JS interop, e.g. waiting for JS promises.
* [RPython](https://github.com/soIu/rpython) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2023-06-16 - A RPython (PyPy's Restricted Python) to WebAssembly compiler
* [TPython](https://github.com/soIu/tpython) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2022-07-25 - Pythonic++ (a "dialect" of C++) to WebAssembly compiler

***

### <a name="prolog"></a>Prolog <sup>[top⇈](#contents)</sup>

> Prolog is a general-purpose logic programming language associated with artificial intelligence and computational linguistics. Prolog has its roots in first-order logic, a formal logic, and unlike many other programming languages, Prolog is intended primarily as a declarative programming language: the program logic is expressed in terms of relations, represented as facts and rules. A computation is initiated by running a query over these relations.

* [Ciao Prolog](https://github.com/ciao-lang/ciao) ⭐ 349 | 🐛 49 | 🌐 Prolog | 📅 2025-06-21 - includes a WebAssembly compilation target based on Emscripten. Ciao Prolog is a modern Prolog implementation designed to be portable, extensible and modular. Check the playground [here](https://ciao-lang.org/playground).
* [SWI-Prolog port to WebAssembly](https://github.com/SWI-Prolog/swipl-wasm) ⚠️ Archived - a port of SWI-Prolog to WebAssembly. SWI-Prolog is a free implementation of the programming language Prolog commonly used for teaching and semantic web applications.

***

### <a name="r"></a>R <sup>[top⇈](#contents)</sup>

> R is a language and environment for statistical computing and graphics.

* [WebR](https://github.com/georgestagg/webR) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-17 - R in the Browser. You can try it out [here](https://webr.r-wasm.org/latest/)

***

### <a name="rebol"></a>Rebol <sup>[top⇈](#contents)</sup>

> Homoiconic ("data is code" and vice-versa) dynamic programming language and data-format (representing data and metadata) language.
>
> By its author, "Rebol rebels against the idea that modern software must be large and complex".

* [Rye](https://github.com/refaktor/rye) ⭐ 702 | 🐛 7 | 🌐 Go | 📅 2026-08-22 - Rye is a high level, dynamic programming language based on ideas from Rebol, flavored by Factor, \*nix shells and Golang. Implemented in Golang. You can try it out [here](https://ryelang.org/).
* [Ren-C](https://github.com/metaeducation/ren-c) ⭐ 140 | 🐛 84 | 🌐 C | 📅 2026-07-16 - Ren-C is a deeply redesigned derivative of the Rebol 3 codebase. Features "user-friendly" API for C and JavaScript. It has WASM-powered [Ren-C's replpad-js](https://github.com/hostilefork/replpad-js) ⭐ 14 | 🐛 36 | 🌐 JavaScript | 📅 2025-12-16 - interactive Web Console for Rebol language (Ren-C branch).

***

### <a name="rego"></a>Rego <sup>[top⇈](#contents)</sup>

> Open Policy Agent (OPA) is an open source, general-purpose policy engine that unifies policy enforcement across the stack. Rego is a high-level declarative policy language purpose-built for expressing policies over complex hierarchical data structures.

* [OPA-Wasm](https://github.com/open-policy-agent/opa/tree/main/wasm) ⭐ 12,180 | 🐛 335 | 🌐 Go | 📅 2026-08-31 - Compilation and evaluation of Rego policies using Wasm.
* [npm-opa-wasm](https://github.com/open-policy-agent/npm-opa-wasm) ⭐ 158 | 🐛 16 | 🌐 JavaScript | 📅 2026-07-10 - NPM module providing an SDK for using Wasm compiled OPA policies.
* [rust-opa-wasm](https://github.com/matrix-org/rust-opa-wasm) ⭐ 79 | 🐛 13 | 🌐 Rust | 📅 2026-08-24 - A crate to use OPA policies compiled to Wasm.
* [dotnet-opa-wasm](https://github.com/christophwille/dotnet-opa-wasm) ⭐ 45 | 🐛 9 | 🌐 C# | 📅 2026-05-26 - Call OPA policies in Wasm from C# .NET Core.
* [java-opa-wasm](https://github.com/sangkeon/java-opa-wasm) ⭐ 18 | 🐛 4 | 🌐 Java | 📅 2024-04-10 - OPA Wasm SDK for Java.
* [python-opa-wasm](https://github.com/a2d24/python-opa-wasm) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2023-06-25 - OPA Wasm SDK for Python.

***

### <a name="ring"></a>Ring <sup>[top⇈](#contents)</sup>

> Ring is a Simple, Small, and Flexible practical general-purpose multi-paradigm language. The supported programming paradigms are Imperative, Procedural, Object-Oriented, Functional, Metaprogramming, Declarative programming using nested structures, and Natural programming.
> The language is portable (MS-DOS, Windows, Linux, macOS, Android, WebAssembly, etc.) and can be used to create Console, GUI, Web, Games, and Mobile applications.

* [Ring](https://github.com/ring-lang/ring) ⭐ 1,461 | 🐛 0 | 🌐 C | 📅 2026-08-31 - main repository. You can try it out [here](https://tio.run/#ring).
* [WASM apps in Ring](https://ring-lang.github.io/doc1.19/qtwebassembly.html#online-applications) - list of demo web applications implemented in Ring.

***

### <a name="roc"></a>Roc <sup>[top⇈](#contents)</sup>

> A fast, friendly, functional language. Compiles to machine code or WASM. Roc is a direct descendant of the Elm programming language.

* [roc](https://github.com/roc-lang/roc) ⭐ 6,017 | 🐛 192 | 🌐 Zig | 📅 2026-08-31 - main repository. You can try it out [here](https://www.roc-lang.org/#try-roc).
* [basic-cli](https://github.com/roc-lang/basic-cli) ⭐ 120 | 🐛 23 | 🌐 Rust | 📅 2026-08-25 - a Roc [platform](https://github.com/roc-lang/roc/wiki/Roc-concepts-explained#platform) ⭐ 6,017 | 🐛 192 | 🌐 Zig | 📅 2026-08-31 to work with files, commands, HTTP, TCP, command line arguments, etc.
* [basic-webserver](https://github.com/roc-lang/basic-webserver) ⭐ 106 | 🐛 11 | 🌐 HTML | 📅 2026-08-30 - a basic Web Server for Roc.

***

### <a name="ruby"></a>Ruby <sup>[top⇈](#contents)</sup>

> Ruby is an open source interpreted high-level programming language for general-purpose programming. Created by Matz. Ruby has a design philosophy that emphasizes code readability, notably using as few sigils (special chars`:.{}%[]&=>;`) as possible.

* [Artichoke](https://github.com/artichoke/artichoke/blob/f8e9881403a50c3ba7e2b1ffc16f205c0b5e0255/VISION.md#design-and-goals) ⚠️ Archived - a Ruby implementation written in Rust and Ruby. You can try it out here: <https://artichoke.run>
* [ruby.wasm](https://github.com/ruby/ruby.wasm/) ⭐ 873 | 🐛 40 | 🌐 Ruby | 📅 2026-08-31 - a collection of "official" WebAssembly ports of the CRuby. You can
  try it out [here](https://try.ruby-lang.org/playground/#code=puts+RUBY_DESCRIPTION\&engine=cruby-3.2.0)
* [run.rb](https://github.com/jasoncharnes/run.rb) ⭐ 597 | 🐛 31 | 🌐 JavaScript | 📅 2022-12-10 run.rb - allows you to run Ruby code in the browser
* [WebAssembly Language Runtimes](https://github.com/vmware-labs/webassembly-language-runtimes) ⭐ 369 | 🐛 28 | 🌐 Shell | 📅 2024-06-05 - up-to-date MRI Ruby prebuilt for WASI
* [Ruvy](https://github.com/Shopify/ruvy) ⚠️ Archived - toolchain for bundling ruby.wasm pre-initialized and bundled with Ruby code
* [rlang](https://github.com/ljulliar/rlang) ⭐ 39 | 🐛 0 | 🌐 Ruby | 📅 2022-11-16 Rlang - a (subset of) Ruby to WebAssembly compiler
* [cry-wasm](https://github.com/kojix2/cry-wasm) ⭐ 33 | 🐛 1 | 🌐 Ruby | 📅 2026-06-19 - speeds up Ruby code using Crystal. By applying simple type restrictions to Ruby code, convert it to Crystal code, compile it to WebAssembly, and call it with Wasmer or Wasmtime.
* [Wruby](https://github.com/pannous/wruby) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2018-11-19 Web ruby - a port of minimal ruby (mruby).

***

### <a name="rust"></a>Rust <sup>[top⇈](#contents)</sup>

> Rust is a systems programming language sponsored by Mozilla Research, which describes it as a "safe, concurrent, practical language,"supporting functional and imperative-procedural paradigms. Rust is syntactically similar to C++, but its designers intend it to provide better memory safety while maintaining performance.

* [Wasm-Bindgen](https://github.com/rustwasm/wasm-bindgen) ⭐ 9,131 | 🐛 557 | 🌐 Rust | 📅 2026-08-28 - A library and a CLI for Rust that facilitate high-level interactions between wasm modules and JavaScript.
* [CargoWeb](https://github.com/koute/cargo-web) ⭐ 1,111 | 🐛 107 | 🌐 Rust | 📅 2023-11-29 - This cargo subcommand aims to make it easy and convenient to build, develop and deploy client-side Web applications written in Rust.
* [Wargo](https://github.com/lord/wargo) ⚠️ Archived - a simple npm package that makes compiling Rust to WebAssembly easy on macOS or Linux.
* [Woz](https://github.com/alexkehayias/woz) ⚠️ Archived - Woz is a WebAssembly progressive web app (PWA) toolchain for building and deploying performant mobile apps with Rust. Distributing your app is as simple as sharing a hyperlink.
* [RustWasmLoader](https://github.com/ianjsikes/rust-wasm-loader) ⭐ 82 | 🐛 2 | 🌐 JavaScript | 📅 2019-06-20 - A simple Webpack loader that shells out to cargo to build a Rust project targeting WebAssembly.
* [Rust `wasm32-unknown-unknown` target](https://www.hellorust.com/setup/wasm-target/) - Rust compiler backend for WebAssembly (without the need for Emscripten).

***

### <a name="scheme"></a>Scheme <sup>[top⇈](#contents)</sup>

> Scheme is a programming language that supports multiple paradigms, including functional programming and imperative programming, and is one of the two main dialects of Lisp. Unlike Common Lisp, the other main dialect, Scheme follows a minimalist design philosophy specifying a small standard core with powerful tools for language extension..

* [Schism](https://github.com/schism-lang/schism) ⭐ 221 | 🐛 2 | 📅 2020-06-02 - Schism is an experimental self-hosting compiler from a subset of R6RS Scheme to WebAssembly. Development so far has focused on features necessary for self-hosting. The compiler itself is written in, and compiles, a very small subset of Scheme.
* [scheme.wasm](https://github.com/pollrobots/scheme) ⭐ 182 | 🐛 109 | 🌐 WebAssembly | 📅 2023-05-02 - An R7RS Scheme implemented in WebAssembly. You can try it out [here](https://pollrobots.com/scheme/).
* [Guile Hoot](https://gitlab.com/spritely/guile-hoot) - a Scheme to WebAssembly compiler backend for GNU Guile and a general purpose WASM toolchain.

***

### <a name="speedyjs"></a>Speedy.js <sup>[top⇈](#contents)</sup>

> Speedy.js is a compiler for a well considered, performance pitfalls free subset of JavaScript targeting WebAssembly. Because WebAssembly is statically-typed, the project uses TypeScript as type-checker and to resolve the types of the program symbols.

* ~~[Speedy.js](https://github.com/MichaReiser/speedy.js) ⚠️ Archived - main repository.~~ `Unmaintained`

***

### <a name="swift"></a>Swift <sup>[top⇈](#contents)</sup>

> Swift is a general-purpose, multi-paradigm, compiled programming language developed by Apple Inc. for iOS, macOS, watchOS, tvOS, Linux, and z/OS.

* [SwiftWasm](https://github.com/swiftwasm) - GitHub organization.

***

### <a name="tcl"></a>Tcl <sup>[top⇈](#contents)</sup>

> Tcl (Tool Command Language) is a very powerful but easy to learn dynamic programming language, mature but evolving, highly extensible and suitable for a very wide range of uses.

* [Wacl](https://github.com/ecky-l/wacl) ⭐ 92 | 🐛 2 | 🌐 JavaScript | 📅 2017-05-29 - A Tcl distibution for WebAssembly or Javascript. Features JS/DOM bindings. You can try it out [here](https://ecky-l.github.io/wacl/).

***

### <a name="theta"></a>Theta <sup>[top⇈](#contents)</sup>

> Theta is a modern, general purpose, functional programming language with a strong type system and expressive syntax. It features a modular design and supports pattern matching, function overloading, and other goodies.

* [ThetaLang](https://github.com/alexdovzhanyn/ThetaLang) ⭐ 43 | 🐛 19 | 🌐 C++ | 📅 2024-11-03 - main repository.

***

### <a name="turboscript"></a>TurboScript <sup>[top⇈](#contents)</sup>

> TurboScript is an experimental programming language for parallel programming for web which compiles to JavaScript (asm.js) and WebAssembly (targeting post-MVP). The syntax is similar to TypeScript and the compiler is open source and written in TypeScript. TurboScript has zero dependencies.

* [TurboScript](https://github.com/01alchemist/TurboScript) ⚠️ Archived - main repository.

***

### <a name="typescript"></a>TypeScript <sup>[top⇈](#contents)</sup>

> TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language.

* See [AssemblyScript](#assemblyscript)

***

### <a name="uxn"></a>Uxn<sup>[top⇈](#contents)</sup>

> Uxn is a small virtual machine specfication, designed for portability and stability.

* [Uxn.wasm](https://github.com/remko/uxn.wasm) ⭐ 57 | 🐛 3 | 🌐 WebAssembly | 📅 2024-08-15 - WebAssembly implementation of the Uxn virtual machine

***

### <a name="v"></a>V <sup>[top⇈](#contents)</sup>

> V is a statically typed compiled programming language designed for building maintainable software.

* [V](https://github.com/vlang/v) ⭐ 37,806 | 🐛 117 | 🌐 V | 📅 2026-08-31 - main repository. You can try it out [here](https://play.vlang.io/)

***

### <a name="virgil"></a>Virgil <sup>[top⇈](#contents)</sup>

> A fast and lightweight safe, garbage-collected systems programming language. Its compiler produces optimized, standalone native executables, WebAssembly modules, or JARs for the JVM.

* [Virgil](https://github.com/titzer/virgil) ⭐ 1,416 | 🐛 35 | 🌐 Shell | 📅 2026-08-27 - main repository.

***

### <a name="wa"></a>Wa <sup>[top⇈](#contents)</sup>

> Wa is a general-purpose programming language designed for developing robustness and maintainability WebAssembly software. Instead of requiring complex toolchains to set up, you can simply go install it - or run it in a browser.

> 凹语言™（凹读音“Wa”）是 针对 WASM 平台设计的的通用编程语言，支持 Linux、macOS 和 Windows 等主流操作系统和 Chrome 等浏览器环境，同时也支持作为独立Shell脚本和被嵌入脚本模式执行。

* [Wa/凹语言(仓库)](https://github.com/wa-lang/wa) ⭐ 1,767 | 🐛 6 | 🌐 Go | 📅 2026-04-30 - main repository.
* [Wa/凹语言(English)](https://wa-lang.github.io/) - Design for WebAssembly.
* [Wa/凹语言(简体中文)](https://wa-lang.org/) - 凹语言 - 为 WebAssembly 而生.

***

### <a name="wah"></a>Wah <sup>[top⇈](#contents)</sup>

> Wah is a slightly higher level language that is a superset of WebAssembly. It aims to make WebAssembly's text format slightly more friendly to humans, without introducing new syntax or datatypes.

* ~~[Wah](https://github.com/tmcw/wah) ⭐ 159 | 🐛 0 | 🌐 Clojure | 📅 2019-07-28 - main repository.~~ `Unmaintained`

***

### <a name="walt"></a>WAlt <sup>[top⇈](#contents)</sup>

> WAlt is an alternative syntax for WebAssembly text format. It's an experiment for using JavaScript syntax to write to as 'close to the metal' as possible. It's JavaScript with rules. .walt files compile directly to WebAssembly binary format.

* ~~[Walt](https://github.com/ballercat/walt) ⭐ 4,631 | 🐛 27 | 🌐 JavaScript | 📅 2023-01-02 - main repository.~~ `Unmaintained`

***

### <a name="wam"></a>Wam <sup>[top⇈](#contents)</sup>

> WebAssembly Macro language: Wam syntax is a near superset of wast syntax that is more convenient for human developers to write directly.

* ~~[Wam](https://github.com/kanaka/wam) ⭐ 67 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-07 - main repository.~~ `Unmaintained`

***

### <a name="wase"></a>Wase <sup>[top⇈](#contents)</sup>

> WASE: WebAssembly made easy. Wase is a language, which tries to make WASM easy to write. The language maps closely to WebAssembly, and compiles directly to Wasm bytecode. Has strong typing with type inference.

* [Wase](https://github.com/area9innovation/wase) ⭐ 46 | 🐛 0 | 🌐 WebAssembly | 📅 2023-03-08 - main repository.

***

### <a name="webassembly"></a>WebAssembly <sup>[top⇈](#contents)</sup>

> Yes, WebAssembly. `Wasm3` is the fastest WebAssembly interpreter, that enables WebAssembly self-hosting.

* [Wasm3](https://github.com/wasm3/wasm3) ⭐ 8,011 | 🐛 19 | 🌐 C | 📅 2026-08-31 - main repository.
* [Wasm3 on WAPM](https://wapm.io/package/vshymanskyy/wasm3) - WAPM package.

***

### <a name="wonkey"></a>Wonkey <sup>[top⇈](#contents)</sup>

> Wonkey is an easy to learn, object-oriented, modern and cross-platform programming language for creating cross-platform video games, highly inspired by the "BlitzBasic" range of languages.

* [Wonkey](https://github.com/wonkey-coders/wonkey) ⭐ 147 | 🐛 0 | 🌐 C++ | 📅 2026-05-31 - main repository. Check the demo games [here](https://wonkey-coders.github.io/examples/).

***

### <a name="wracket"></a>Wracket <sup>[top⇈](#contents)</sup>

> A lisp-like language that compiles to WebAssembly, written in racket

* ~~[Wracket](https://github.com/sschauss/wracket) ⭐ 23 | 🐛 0 | 🌐 Racket | 📅 2017-11-26 - main repository.~~ `Unmaintained`

***

### <a name="xcc"></a>xcc <sup>[top⇈](#contents)</sup>

> Toy C compiler for x86-64 and wasm

* [xcc](https://github.com/tyfkda/xcc) ⭐ 546 | 🐛 22 | 🌐 C | 📅 2026-08-30 - main repository.
* [Online demo](https://tyfkda.github.io/xcc/).

***

### <a name="zig"></a>Zig <sup>[top⇈](#contents)</sup>

> Zig is a general-purpose programming language designed for robustness, optimality, and maintainability.

* [Zig WebAssembly](https://ziglang.org/documentation/master/#WebAssembly) - documentation on WebAssembly

***

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

***

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Akinyemi](https://github.com/appcypher) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._
