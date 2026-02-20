# C Mastery Roadmap

*The language that built the modern world. No runtime, no safety nets, no excuses.*

**Status:** ⚪ Not Started  
**Started:** TBD  
**Target Completion:** TBD

---

## 📋 Mastery Checklist

### Part I: Foundations – The Absolute Basics
- [ ] [History – Why C exists, where it's used](/track-02-systems/01-c/notes/01-history.md)
- [ ] [Structure of a C Program – `main()`, headers](/track-02-systems/01-c/notes/02-program-structure.md)
- [ ] [Compilation – Preprocessor, compiler, linker, assembler](/track-02-systems/01-c/notes/03-compilation.md)
- [ ] [Basic Types – `int`, `char`, `float`, `double`](/track-02-systems/01-c/notes/04-basic-types.md)
- [ ] [Variables – Declaration, initialization, scope](/track-02-systems/01-c/notes/05-variables.md)
- [ ] [Constants – `const`, `#define`, enums](/track-02-systems/01-c/notes/06-constants.md)
- [ ] [Operators – Arithmetic, relational, logical, bitwise](/track-02-systems/01-c/notes/07-operators.md)
- [ ] [Control Flow – `if`, `else`, `switch`](/track-02-systems/01-c/notes/08-control-flow.md)
- [ ] [Loops – `for`, `while`, `do-while`](/track-02-systems/01-c/notes/09-loops.md)

**Project:** [Hello World and Variations](/track-02-systems/01-c/projects/01-hello-world/)

---

### Part II: Functions – The Building Blocks
- [ ] [Function Syntax – Return type, parameters, body](/track-02-systems/01-c/notes/10-function-syntax.md)
- [ ] [Pass by Value – Everything is a copy](/track-02-systems/01-c/notes/11-pass-by-value.md)
- [ ] [Function Prototypes – Declaration vs definition](/track-02-systems/01-c/notes/12-prototypes.md)
- [ ] [Scope and Lifetime – Local, global, static](/track-02-systems/01-c/notes/13-scope.md)
- [ ] [Recursion – Base cases, stack depth](/track-02-systems/01-c/notes/14-recursion.md)
- [ ] [Inline Functions – Hinting the compiler](/track-02-systems/01-c/notes/15-inline.md)
- [ ] [Variadic Functions – `stdarg.h`, `printf`-like](/track-02-systems/01-c/notes/16-variadic.md)

**Project:** [Function Library](/track-02-systems/01-c/projects/02-function-library/)

---

### Part III: Arrays and Strings
- [ ] [Arrays – Declaration, initialization, access](/track-02-systems/01-c/notes/17-arrays.md)
- [ ] [Multidimensional Arrays – Rows and columns](/track-02-systems/01-c/notes/18-multidimensional.md)
- [ ] [Strings – Character arrays, null terminator](/track-02-systems/01-c/notes/19-strings.md)
- [ ] [String Functions – `string.h`, `strlen`, `strcpy`, etc.](/track-02-systems/01-c/notes/20-string-functions.md)
- [ ] [Array and Pointer Relationship](/track-02-systems/01-c/notes/21-array-pointer.md)
- [ ] [Array of Strings – `char *argv[]`](/track-02-systems/01-c/notes/22-array-of-strings.md)

**Project:** [String Manipulation Library](/track-02-systems/01-c/projects/03-string-library/)

---

### Part IV: Pointers – The Heart of C
- [ ] [What is a Pointer? – Memory addresses](/track-02-systems/01-c/notes/23-pointer-basics.md)
- [ ] [Pointer Operators – `&` (address), `*` (dereference)](/track-02-systems/01-c/notes/24-pointer-operators.md)
- [ ] [Pointer Arithmetic – Moving through memory](/track-02-systems/01-c/notes/25-pointer-arithmetic.md)
- [ ] [Null Pointers – `NULL`, nullptr, dangers](/track-02-systems/01-c/notes/26-null.md)
- [ ] [Pointers and Functions – Pass by pointer](/track-02-systems/01-c/notes/27-pointer-parameters.md)
- [ ] [Pointers to Pointers – `**`](/track-02-systems/01-c/notes/28-pointer-to-pointer.md)
- [ ] [Function Pointers – Callbacks, jump tables](/track-02-systems/01-c/notes/29-function-pointers.md)
- [ ] [Void Pointers – `void*`, generic pointers](/track-02-systems/01-c/notes/30-void-pointers.md)

**Project:** [Pointer Explorer](/track-02-systems/01-c/projects/04-pointer-explorer/)

---

### Part V: Memory Management
- [ ] [Stack vs Heap – Lifetime and size differences](/track-02-systems/01-c/notes/31-stack-heap.md)
- [ ] [Static Allocation – Compile-time fixed size](/track-02-systems/01-c/notes/32-static-allocation.md)
- [ ] [Dynamic Allocation – `malloc`, `calloc`, `realloc`](/track-02-systems/01-c/notes/33-dynamic-allocation.md)
- [ ] [Freeing Memory – `free`, dangling pointers](/track-02-systems/01-c/notes/34-free.md)
- [ ] [Memory Leaks – Detection and prevention](/track-02-systems/01-c/notes/35-memory-leaks.md)
- [ ] [Memory Layout – Text, data, bss, heap, stack](/track-02-systems/01-c/notes/36-memory-layout.md)
- [ ] [Alignment and Padding – Structure packing](/track-02-systems/01-c/notes/37-alignment.md)

**Project:** [Dynamic Array Implementation](/track-02-systems/01-c/projects/05-dynamic-array/)

---

### Part VI: Structures and Unions
- [ ] [Structures – `struct`, grouping data](/track-02-systems/01-c/notes/38-structures.md)
- [ ] [Structure Padding – Why sizeof lies](/track-02-systems/01-c/notes/39-struct-padding.md)
- [ ] [Pointers to Structures – `->` operator](/track-02-systems/01-c/notes/40-struct-pointers.md)
- [ ] [Nested Structures](/track-02-systems/01-c/notes/41-nested-structs.md)
- [ ] [Unions – Overlapping memory](/track-02-systems/01-c/notes/42-unions.md)
- [ ] [Bit Fields – Packing flags](/track-02-systems/01-c/notes/43-bit-fields.md)
- [ ] [`typedef` – Creating type aliases](/track-02-systems/01-c/notes/44-typedef.md)

**Project:** [Data Structure Library](/track-02-systems/01-c/projects/06-data-structures/)

---

### Part VII: Input/Output
- [ ] [Standard I/O – `stdio.h`](/track-02-systems/01-c/notes/45-stdio.md)
- [ ] [Formatted Output – `printf` family](/track-02-systems/01-c/notes/46-printf.md)
- [ ] [Formatted Input – `scanf` family and pitfalls](/track-02-systems/01-c/notes/47-scanf.md)
- [ ] [File I/O – `fopen`, `fclose`, `fread`, `fwrite`](/track-02-systems/01-c/notes/48-file-io.md)
- [ ] [Line-by-line Reading – `fgets`, `getline`](/track-02-systems/01-c/notes/49-line-reading.md)
- [ ] [Binary vs Text Files](/track-02-systems/01-c/notes/50-binary-text.md)
- [ ] [Error Handling – `ferror`, `perror`](/track-02-systems/01-c/notes/51-file-errors.md)

**Project:** [File Processor](/track-02-systems/01-c/projects/07-file-processor/)

---

### Part VIII: Preprocessor
- [ ] [Preprocessor Directives – `#include`, `#define`](/track-02-systems/01-c/notes/52-preprocessor.md)
- [ ] [Macros – Object-like, function-like](/track-02-systems/01-c/notes/53-macros.md)
- [ ] [Conditional Compilation – `#ifdef`, `#ifndef`, `#if`](/track-02-systems/01-c/notes/54-conditional.md)
- [ ] [Macro Pitfalls – Double evaluation, parentheses](/track-02-systems/01-c/notes/55-macro-pitfalls.md)
- [ ] [Stringification – `#` operator](/track-02-systems/01-c/notes/56-stringification.md)
- [ ] [Concatenation – `##` operator](/track-02-systems/01-c/notes/57-concatenation.md)
- [ ] [Predefined Macros – `__FILE__`, `__LINE__`, etc.](/track-02-systems/01-c/notes/58-predefined.md)

**Project:** [Debug Macros](/track-02-systems/01-c/projects/08-debug-macros/)

---

### Part IX: Advanced Pointers
- [ ] [Complex Declarations – Reading right-to-left](/track-02-systems/01-c/notes/59-complex-declarations.md)
- [ ] [Pointer to Array vs Array of Pointers](/track-02-systems/01-c/notes/60-pointer-array-confusion.md)
- [ ] [Pointer to Function Returning Pointer...](/track-02-systems/01-c/notes/61-extreme-pointers.md)
- [ ] [Restrict Keyword – Aliasing hints](/track-02-systems/01-c/notes/62-restrict.md)
- [ ] [Volatile – Preventing optimizations](/track-02-systems/01-c/notes/63-volatile.md)

**Project:** [Pointer Puzzle Solver](/track-02-systems/01-c/projects/09-pointer-puzzles/)

---

### Part X: Libraries and Linking
- [ ] [Static Libraries – `.a` files, `ar`](/track-02-systems/01-c/notes/64-static-libraries.md)
- [ ] [Shared Libraries – `.so`, `.dll`, `.dylib`](/track-02-systems/01-c/notes/65-shared-libraries.md)
- [ ] [Dynamic Loading – `dlopen`, `dlsym`](/track-02-systems/01-c/notes/66-dynamic-loading.md)
- [ ] [Header Guards – Preventing multiple inclusion](/track-02-systems/01-c/notes/67-header-guards.md)
- [ ] [Linker Scripts – Advanced control](/track-02-systems/01-c/notes/68-linker-scripts.md)

**Project:** [Library Creator](/track-02-systems/01-c/projects/10-library-creator/)

---

### Part XI: System Programming
- [ ] [Processes – `fork`, `exec`, `wait`](/track-02-systems/01-c/notes/69-processes.md)
- [ ] [Signals – `signal`, `kill`, handling](/track-02-systems/01-c/notes/70-signals.md)
- [ ] [Pipes – Inter-process communication](/track-02-systems/01-c/notes/71-pipes.md)
- [ ] [Sockets – Network programming basics](/track-02-systems/01-c/notes/72-sockets.md)
- [ ] [File Descriptors – Low-level I/O](/track-02-systems/01-c/notes/73-file-descriptors.md)
- [ ] [Memory Mapping – `mmap`](/track-02-systems/01-c/notes/74-mmap.md)
- [ ] [Threads – POSIX threads (pthreads)](/track-02-systems/01-c/notes/75-threads.md)
- [ ] [Synchronization – Mutexes, condition variables](/track-02-systems/01-c/notes/76-synchronization.md)

**Project:** [Mini Web Server](/track-02-systems/01-c/projects/11-mini-server/)

---

### Part XII: Debugging and Tools
- [ ] [GDB – The GNU Debugger](/track-02-systems/01-c/notes/77-gdb.md)
- [ ] [Valgrind – Memory error detection](/track-02-systems/01-c/notes/78-valgrind.md)
- [ ] [Address Sanitizer – Modern memory checking](/track-02-systems/01-c/notes/79-asan.md)
- [ ] [Make – Build automation](/track-02-systems/01-c/notes/80-make.md)
- [ ] [CMake – Cross-platform builds](/track-02-systems/01-c/notes/81-cmake.md)
- [ ] [Static Analysis – `lint`, `clang-tidy`](/track-02-systems/01-c/notes/82-static-analysis.md)
- [ ] [Profiling – `gprof`, `perf`](/track-02-systems/01-c/notes/83-profiling.md)

**Project:** [Debugging Exercise Suite](/track-02-systems/01-c/projects/12-debugging-exercises/)

---

### Part XIII: Undefined Behavior
- [ ] [What is Undefined Behavior?](/track-02-systems/01-c/notes/84-ub.md)
- [ ] [Common UB – Overflow, null dereference, etc.](/track-02-systems/01-c/notes/85-ub-common.md)
- [ ] [UB and Optimization – Compiler assumptions](/track-02-systems/01-c/notes/86-ub-optimization.md)
- [ ] [Implementation-Defined Behavior](/track-02-systems/01-c/notes/87-implementation-defined.md)
- [ ] [Unspecified Behavior](/track-02-systems/01-c/notes/88-unspecified.md)

**Project:** [UB Hunter](/track-02-systems/01-c/projects/13-ub-hunter/)

---

### Part XIV: C Standards
- [ ] [K&R C – The original](/track-02-systems/01-c/notes/89-kr.md)
- [ ] [ANSI C (C89/C90) – Standardization](/track-02-systems/01-c/notes/90-ansi.md)
- [ ] [C99 – Designated initializers, inline, comments](/track-02-systems/01-c/notes/91-c99.md)
- [ ] [C11 – Threads, atomics, `_Generic`](/track-02-systems/01-c/notes/92-c11.md)
- [ ] [C17/C18 – Bug fixes](/track-02-systems/01-c/notes/93-c17.md)
- [ ] [C2x – The future](/track-02-systems/01-c/notes/94-c2x.md)

**Project:** [Standards Explorer](/track-02-systems/01-c/projects/14-standards-explorer/)

---

### Part XV: Real-World C
- [ ] [Reading Others' Code – Linux kernel, git, redis](/track-02-systems/01-c/notes/95-reading-code.md)
- [ ] [Coding Standards – Style, consistency](/track-02-systems/01-c/notes/96-coding-standards.md)
- [ ] [Portability – Writing cross-platform C](/track-02-systems/01-c/notes/97-portability.md)
- [ ] [Embedded C – Constraints and patterns](/track-02-systems/01-c/notes/98-embedded.md)
- [ ] [Security – Buffer overflows, format string attacks](/track-02-systems/01-c/notes/99-security.md)
- [ ] [Interfacing with Other Languages – FFI, Python/C API](/track-02-systems/01-c/notes/100-ffi.md)

**Project:** [Contribute to Open Source C Project](/track-02-systems/01-c/projects/15-open-source/)

---

## 🎯 Capstone Project

After completing all sections, build: **[From-Scratch Implementation](/track-02-systems/01-c/projects/capstone/)**

Choose one:
- A simple garbage collector
- A basic HTTP server
- A memory allocator (like malloc)
- An interpreter for a tiny language
- A game (like tetris) with a simple graphics library

---

## 📚 Resources

- [The C Programming Language (K&R)](https://en.wikipedia.org/wiki/The_C_Programming_Language)
- [Modern C (Gustedt)](https://modernc.gforge.inria.fr/)
- [C Programming: A Modern Approach (King)](http://knking.com/books/c/)
- [Linux man pages](https://man7.org/linux/man-pages/)

---

## 🔗 Cross-Track Connections

| Concept | Connects To |
|---------|-------------|
| Pointers | [Memory management in C++](/track-02-systems/02-cpp/roadmap.md) |
| Memory safety issues | [Rust's ownership model](/track-02-systems/03-rust/roadmap.md) |
| System calls | [Go's syscall package](/track-02-systems/04-go/roadmap.md) |
| Undefined behavior | [Compiler design](/track-05-architecture/02-software-architecture/roadmap.md) |
| Embedded C | [Embedded systems specialization](/track-07-specializations/05-embedded/roadmap.md) |

---

## ✅ Progress Summary

| Section | Status | Completed |
|---------|--------|-----------|
| Part I: Foundations | ⚪ Not Started | 0/9 |
| Part II: Functions | ⚪ Not Started | 0/7 |
| Part III: Arrays and Strings | ⚪ Not Started | 0/6 |
| Part IV: Pointers | ⚪ Not Started | 0/8 |
| Part V: Memory Management | ⚪ Not Started | 0/7 |
| Part VI: Structures and Unions | ⚪ Not Started | 0/7 |
| Part VII: Input/Output | ⚪ Not Started | 0/7 |
| Part VIII: Preprocessor | ⚪ Not Started | 0/7 |
| Part IX: Advanced Pointers | ⚪ Not Started | 0/5 |
| Part X: Libraries and Linking | ⚪ Not Started | 0/5 |
| Part XI: System Programming | ⚪ Not Started | 0/8 |
| Part XII: Debugging and Tools | ⚪ Not Started | 0/7 |
| Part XIII: Undefined Behavior | ⚪ Not Started | 0/5 |
| Part XIV: C Standards | ⚪ Not Started | 0/6 |
| Part XV: Real-World C | ⚪ Not Started | 0/6 |

**Overall:** 0/100 topics (⚪ 0%)

---

## Next: [C++ Roadmap](/track-02-systems/02-cpp/roadmap.md)
