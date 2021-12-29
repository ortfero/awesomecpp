# awesomecpp

Awesome C++ Libraries

## Audio

* [miniaudio](https://miniaud.io/) -- A single file audio playback and capture library.


## Compression

* [LZ4](https://github.com/lz4/lz4) -- Extremely fast compression.


## Configuration

* [taocpp/config](https://github.com/taocpp/config) --  header-only library that reads config files based on JSON and JAXN and produces a single JSON Value as result.
* [Tortellini](https://github.com/Qix-/tortellini) -- ini file reader and writer for C++11 and above.
* [confetti](https://github.com/ortfero/confetti) -- C++17 one-header library to parse ini files with toml extensions.


## Console

* [Lyra](https://github.com/bfgroup/Lyra) -- A simple to use, composing, header only, command line arguments parser for C++ 11 and beyond.
* [oof](https://github.com/s9w/oof) -- Convenient, high-performance RGB color and position control for console output.


## Data Types

* [static_vector](https://github.com/gnzlbg/static_vector) -- dynamically-resizable vector with fixed capacity and embedded storage.
* [robin_hood unordered map & set](https://github.com/martinus/robin-hood-hashin) -- platform independent replacement for `std::unordered_map` / `std::unordered_set` which is both faster and more memory efficient for real-world use cases.
* [NanoRange](https://github.com/tcbrindle/NanoRange) -- C++17 implementation of the C++20 Ranges proposals.
* [pdqsort](https://github.com/orlp/pdqsort) -- pattern-defeating quicksort (pdqsort) is a novel sorting algorithm that combines the fast average case of randomized quicksort with the fast worst case of heapsort, while achieving linear time on inputs with certain patterns.
* [taocpp/operators](https://github.com/taocpp/operators) -- zero-dependency C++11 single-header library that provides highly efficient, move aware operators for arithmetic data types.
* [taocpp/sequences](https://github.com/taocpp/sequences) --  zero-dependency C++11 header-only library that provides efficient algorithms to generate and work on variadic templates and `std::integer_sequence`.
* [flecs](https://github.com/SanderMertens/flecs) -- fast and lightweight Entity Component System with a focus on high performance game development.
* [Little Type Library](https://github.com/qnope/Little-Type-Library) -- lightweight library that can be used for meta programming and / or functional programming.
* [recursive-variant](https://github.com/codeinred/recursive-variant) -- a simple library for recursive variant types.
* [cppitertools](https://github.com/ryanhaining/cppitertools) -- implementation of python itertools and builtin iteration functions for C++17.


## Data Formats

* [taocpp/json](https://github.com/taocpp/json) -- header-only JSON library that provides a generic Value Class, uses Type Traits to interoperate with C++ types, uses an Events Interface to convert from and to JSON, JAXN, CBOR, MsgPack and UBJSON, and much more.
* [simdjson](https://github.com/simdjson/simdjson) -- parsing gigabytes of JSON per second.
* [RapidJSON](https://github.com/Tencent/rapidjson) -- fast JSON parser/generator for C++ with both SAX/DOM style API.
* [Boost.JSON](https://github.com/boostorg/json) -- portable C++ library which provides containers and algorithms that implement JavaScript Object Notation, or simply "JSON", a lightweight data-interchange format.
* [sajson](https://github.com/chadaustin/sajson) -- extremely high-performance, in-place, DOM-style JSON parser written in C++.
* [DAW JSON Link](https://github.com/beached/daw_json_link) -- static JSON parsing in C++.
* [json.h](https://github.com/sheredom/json.h) -- single header json parser for C and C++.
* [lazycsv](https://github.com/ashtum/lazycsv) -- fast, lightweight and single-header c++ csv parser library.


## Database

* [cpp-sqlitelib](https://github.com/yhirose/cpp-sqlitelib) -- C++11 SQLite wrapper library.


## Error Handling

* [expected lite](https://github.com/martinmoene/expected-lite) -- expected objects in C++11 and later in a single-file header-only library.
* [LEAF](https://github.com/boostorg/leaf) -- lightweight error handling library for C++11.


## File Managment

* [TinyDir](https://github.com/cxong/tinydir) -- lightweight, portable and easy to integrate C directory and file reader.
* [cpp-mmaplib](https://github.com/yhirose/cpp-mmaplib) -- C++11 header-only memory mapped file library.


## Graphics

* [raylib](https://github.com/raysan5/raylib) -- simple and easy-to-use library to enjoy videogames programming.
* [WUHOO](https://github.com/ViNeek/wuhoo) -- single-header library for graphics related window management, compatible with both C and C++.
* [HibFonts](https://github.com/hibengler/HibFonts) -- manuscript based ASCII font for Open GL ES 2.0.
* [lunasvg](https://github.com/sammycage/lunasvg) -- standalone c++ library to create, animate, manipulate and render SVG files.
* [PlutoVG](https://github.com/sammycage/plutovg) -- standalone 2D vector graphics library in C.
* [Matplot++](https://github.com/alandefreitas/matplotplusplus) -- graphics library for data visualization.
* [The Forge](https://github.com/ConfettiFX/The-Forge) -- cross-platform rendering framework.
* [LLGL](https://github.com/LukasBanana/LLGL) -- thin abstraction layer for the modern graphics APIs OpenGL, Direct3D, Vulkan, and Metal.
* [Godot](https://github.com/godotengine/godot) -- multi-platform 2D and 3D game engine.
* [Sokol](https://github.com/floooh/sokol) -- minimal cross-platform standalone C headers.

## Logging

* [spdlog](https://github.com/gabime/spdlog) -- fast C++ logging library.
* [reckless](https://github.com/mattiasflodin/reckless) -- Low-latency, high-throughput, asynchronous logging library for C++.
* [Quill](https://github.com/odygrd/quill) -- cross-platform low latency logging library based on C++14.


## Math

* [FastTrigo](https://github.com/divideconcept/FastTrigo) -- fast yet accurate trigonometric functions.
* [vmath](https://github.com/BlackMATov/vmath.hpp) -- C++17 tiny vector math library.
* [fixed_math](https://github.com/arturbac/fixed_math) -- fixed point 48.16 bit arithmetic type.
* [eve](https://github.com/jfalcou/eve) -- expressive velocity engine.


## Microbenchmarking

* [picobench](https://github.com/iboB/picobench) -- tiny microbenchmarking library in a single header file.


## Concurrency

* [Disruptor++](https://github.com/lewissbaker/disruptorplus) -- disruptor thread-synchronisation data structure for C++11.
* [xenium](https://github.com/mpoeter/xenium) -- library providing various concurrent data structures and reclamation schemes.
* [moodycamel::ConcurrentQueue](https://github.com/cameron314/concurrentqueue) -- fast multi-producer, multi-consumer lock-free concurrent queue for C++11.
* [stlab](https://github.com/stlab/libraries) --  library provides futures and channels, high level constructs for implementing algorithms that eases the use of multiple CPU cores while minimizing contention.
* [SObjectizer](https://github.com/Stiffstream/sobjectizer) -- implementation of Actor, Publish-Subscribe, and CSP models in one rather small C++ framework.
* [concurrencpp](https://github.com/David-Haim/concurrencpp) -- tasks, executors, timers and C++20 coroutines to rule them all.
* [libfev](https://github.com/patrykstefanski/libfev) -- library for events and fibers.
* [libunifex](https://github.com/facebookexperimental/libunifex) --  prototype implementation of the C++ sender/receiver async programming model that is currently being considered for standardisation.
* [periodic-function](https://github.com/DeveloperPaul123/periodic-function) -- small header only library to call a function at a specific time interval.
* [cpp-threadpool](https://github.com/yhirose/cpp-threadpool) -- C++11 header-only thread pool library.
* [SCoro](https://github.com/seppeon/SCoro) -- a stackless, resumable, resettable state machine style coroutine library for C++17.

## Network

* [Asio](https://github.com/chriskohlhoff/asio) -- Asio C++ Library.
* [ZeroMQ](https://github.com/zeromq/libzmq) -- library which extends the standard socket interfaces with features traditionally provided by specialised messaging middleware products.
* [nanomsg-next-gen](https://github.com/nanomsg/nng) -- lightweight, broker-less library, offering a simple API to solve common recurring messaging problems, such as publish/subscribe, RPC-style request/reply, or service discovery.
* [FlatBuffers](https://github.com/google/flatbuffers) -- memory efficient serialization library.
* [cpp-httplib](https://github.com/yhirose/cpp-httplib) -- C++11 single-file header-only cross platform HTTP/HTTPS library.
* [kleinsHTTP](https://github.com/kleinschrader/kleinsHTTP) -- a stupid stupidly simple http server.
* [PicoHTTPParser](https://github.com/h2o/picohttpparser) -- tiny HTTP parser written in C.
* [jwt-cpp](https://github.com/Thalhammer/jwt-cpp) -- header only library for creating and validating json web tokens in c++.
* [cpprouter](https://github.com/omartijn/cpprouter) -- modern, header-only request router for C++.


## Parsers

* [cpp-peglib](https://github.com/yhirose/cpp-peglib) -- C++17 header-only PEG (Parsing Expression Grammars) library.


## Process Managment

* [subprocess.h](https://github.com/sheredom/subprocess.h) -- single header process launching solution for C and C++.
* [subprocess](https://github.com/rajatjain1997/subprocess) -- a C++ high level library for running shell processes.


## Scripts

* [Gravity](https://github.com/marcobambini/gravity) -- gravity programming language.
* [Elk](https://github.com/cesanta/elk) -- tiny JS engine for embedded systems.
* [QuickJS](https://github.com/bellard/quickjs) -- QuickJS Javascript Engine.
* [PL/0 JIT compiler](https://github.com/yhirose/pl0-jit-compiler) -- tiny PL/0 JIT compiler in less than 700 LOC with LLVM and PEG parser.
* [Monjey](https://github.com/yhirose/monkey-cpp) --  C++ version monkey language interpreter.


## Storage

* [RocksDB](https://github.com/facebook/rocksdb) -- persistent key-value store for flash and RAM storage.

## UI

* [Dear ImGui](https://github.com/ocornut/imgui) -- bloat-free Graphical User interface for C++ with minimal dependencies.
* [Neutralinojs](https://github.com/neutralinojs) -- portable and lightweight cross platform app development framework.
* [Elements](https://github.com/cycfi/elements) -- lightweight, fine-grained, resolution independent, modular GUI library.
* [raygui](https://github.com/raysan5/raygui) -- simple and easy-to-use immediate-mode gui library.
* [microui](https://github.com/rxi/microui) -- tiny, portable, immediate-mode UI library written in ANSI C.
* [xtd](https://github.com/gammasoft71/xtd) -- modern C++17 / C++20 framework to create console, forms (GUI like WinForms) and unit test applications on Microsoft Windows, Apple macOS and Linux

## Unicode

* [cpp-unicodelib](https://github.com/yhirose/cpp-unicodelib) -- C++17 single-file header-only Unicode library.
* [utf8.h](https://github.com/sheredom/utf8.h) -- single header utf8 string functions for C and C++.


