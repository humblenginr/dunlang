What language are we going to use for building the compiler?
Rust, Go, Zig, C, Ocaml, Haskell

What are the things that you need a programming language to be good at in order for you to build a compiler?

1. Highly Performant
2. Low level capabilities - essential for implementing ASTs and managing memory efficiently
3. Very good type system - helps in easier error handling
4. Support for pattern matching - helps in lexing and parsing

Haskell, OCaml, Rust

Rust can be sometimes too strict.
We can have the same argument with Haskell as well. We are restricted to writing only pure code when we use Haskell, and that can sometimes make things harder.

Therefore we will be using Ocaml for this project.

- https://borretti.me/article/lessons-writing-compiler
- https://www.quora.com/What-is-the-best-programming-language-to-use-when-writing-a-compiler-e-g-ML-Lisp-Java-C++-Python-et-cetera#:~:text=Here%20are%20some%20commonly%20used,to%20write%20high%2Dperformance%20compilers.
- https://cs.lmu.edu/~ray/notes/languagedesignnotes/
