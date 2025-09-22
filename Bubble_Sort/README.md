# Bubble Sort

**Bubble Sort** is a simple comparison-based sorting algorithm. It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted.

### Characteristics

- **Time Complexity**:  
  - Best case: `O(n)` — when the list is already sorted (with optimization).  
  - Average case: `O(n²)` — typical performance on random data.  
  - Worst case: `O(n²)` — when the list is sorted in reverse order.

- **Space Complexity**: `O(1)` — sorts in place; requires only a constant amount of additional memory.

- **Stability**: Stable — equal elements retain their relative order.

- **Requirements**:  
  - Only requires the ability to compare and swap adjacent elements.  
  - Works with any data type that supports comparison operations.

### When to Use

- Educational purposes — excellent for learning sorting fundamentals.
- Small datasets where performance is not critical.
- Situations where code simplicity is more important than efficiency.
- Prototyping or debugging sorting logic.

---

## Implementations

This directory contains implementations of Bubble Sort in multiple programming languages.

| Imperative / Procedural       | Object-oriented          | Functional         | Multi-paradigm        |
|-------------------------------|--------------------------|--------------------|-----------------------|
| [Pascal](Pascal/bubble_sort.pas)         | [Java](Java/BubbleSort.java)               | [Haskell](Haskell/bubble_sort.hs)         | [Python](Python/bubble_sort.py)           |
| [Fortran](Fortran/bubble_sort.f90)       | [C#](Csharp/BubbleSort.cs)                 | [R](R/bubble_sort.r)                      | [C++](C++/bubble_sort.cpp)                |
| [C](C/bubble_sort.c)                     | [Swift](Swift/BubbleSort.swift)            | [Elixir](Elixir/bubble_sort.ex)           | [Rust](Rust/bubble_sort.rs)               |
| [COBOL](Cobol/bubble_sort.cbl)           | [Kotlin](Kotlin/BubbleSort.kt)             | [Scala](Scala/BubbleSort.scala)           | [Go](Go/bubble_sort.go)                   |
| [Ada](Ada/bubble_sort.adb)               | [Visual Basic](Visual_Basic/BubbleSort.vb) | [Erlang](Erlang/bubble_sort.erl)          | [JavaScript](JavaScript/bubble_sort.js)   |
| [Assembler (NASM)](Assembler(NASM)/bubble_sort.asm)                           |                          |                    | [TypeScript](TypeScript/bubble_sort.ts)   |
|                               |                          |                    | [PHP](PHP/bubble_sort.php)                |
|                               |                          |                    | [Perl](Perl/bubble_sort.pl)               |
|                               |                          |                    | [MATLAB](MATLAB/bubble_sort.m)            |
|                               |                          |                    | [Dart](Dart/bubble_sort.dart)             |
|                               |                          |                    | [Zig](Zig/bubble_sort.zig)                |
|                               |                          |                    | [Ruby](Ruby/bubble_sort.rb)               |
|                               |                          |                    | [Lua](Lua/bubble_sort.lua)                |

## Notes

- For languages where local environment setup is difficult, online compilers or interpreters were used for testing.
- To improve the understanding of the code, a file has been added in the appropriate language directories README.md Since the syntax of the language required additional study, the README provides a step-by-step guide with detailed comments on each section of the code and an explanation of the language features used.
