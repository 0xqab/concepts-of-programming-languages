# Concepts of Programming Languages
Master Course: Concepts of Programming Languages - Rosenheim Technical University - 2019/2020

<img src="docs/img/go.png" width="10%">

The course "Concepts of Programming Languages" is designed as a master course. Solid programming skills in Java/C/C++ are required. I also assume that students have introductory skills in Scala and Python. For all exercises and examples, the course uses Go (Golang) as concrete example.
We will look at typical styles and application areas like OOP, FP, Parallel-, Distributed- or Systems Programming. 

## Goal of the Course

1. Learn the Concepts of Programming Languages
2. Learn how Go differs from Java, C/C++, Scala and languages
3. Get solid skills to pick the right language for a given problem

It is somewhat unusual, that we focus on Go in all Lectures. Master students are typically well skilled in Java. They
have some basic knowledge in C/C++, maybe JavaScript, Ruby, Python or Scala. Since Go is a multi paradigm language, the lecture uses Go to demonstrate the basic concepts of these languages and discuss features which are missing in Go. We go from concrete to the abstraction and not vice versa.
Each student will compare Go to one of these languages as Semester Work: Modula, Ada, Smalltalk, C++, Eiffel, Objective C, Haskell, Clojure, F# , Erlang, Scala, D, Occam, Rust, Swift, JavaScript, Ruby, Python, Kotlin. We will release the results here. 

## Lecture 1 - Introduction

- Overview of Programming Languages, Why Go?
- Setup, HelloWorld, Swap, Basic Types and Variables, Programm Arguments, Working with Go Flags, CLI Libraries 
- <a href="docs/1.0-About.pdf">About</a>
- <a href="docs/1.1-Overview.pdf">Overview</a>
- <a href="docs/1.2-Introduction to Golang.pdf">Introduction to Golang</a>
- <a href="docs/exercises/Exercise1.md">Exercise 1</a>

## Lecture 2 - Basics in Go Programming, OOP Part I

- Pointer, Arrays, Maps and Object Oriented Programming
- Reasons for Go https://www.youtube.com/watch?v=5kj5ApnhPAE
- <a href="docs/2.0-Go Programming - Basics and OOP.pdf">Slides</a>
- <a href="docs/exercises/Exercise2.1.md">Exercise 2.1</a>
- <a href="docs/exercises/Exercise2.2.md">Exercise 2.2</a>

## Lecture 3 - Object Oriented Programming in Go, OOP Part II

- Structs, Interfaces, Embedding, Polymorphism
- <a href="docs/3.0-Go-Programming-OOP.pdf">Slides</a>
- <a href="docs/exercises/Exercise3.md">Exercise 3.1 - Interfaces, Polymorphism and Embedding</a>
- <a href="docs/exercises/Exercise3.md">Exercise 3.2 - Mail Component and Service Locator</a>

## Lecture 4 - Building Parsers

- Practicing Go using the example of parsers for boolean expressions
- <a href="docs/4.0-Go-Programming-Parser.pdf">Slides</a>
- <a href="docs/exercises/Exercise4.md">Exercise 4.1 - Lexer for boolean expressions
- <a href="docs/exercises/Exercise4.md">Exercise 4.2.1 - Abstract Syntax Tree (AST)
- <a href="docs/exercises/Exercise4.md">Exercise 4.2.2 Recursive Descent Parser
- <a href="docs/exercises/Exercise4.md">Exercise 4.3 Antlr

## Lecture 5 - Functional Programming
- Introduction in Functional Programming, the Lambda Calculus and the implementation in Go
- <a href="docs/5.0-Functional-Programming.pdf">Slides</a>
- <a href="docs/exercises/Exercise5.md">Exercise 5.1 - Warm Up with functional Programming in Go</a>
- <a href="docs/exercises/Exercise5.md">Exercise 5.2 - Functional Composition</a>
- <a href="docs/exercises/Exercise5.md">Exercise 5.3 - Map, Filter, Reduce with Streams</a>
- <a href="docs/exercises/Exercise5.md">Exercise 5.4 - Functional Word Count</a>

## Lecture 6 - Concurrent Programming
- Why concurrent programming matters! Go routines and channels, Go concurrency patterns, The dining philosophers problem
- <a href="docs/6.0-Concurrent-Programming.pdf">Slides</a>
- <a href="docs/exercises/Exercise6.md">Exercise 6</a>

## Lecture 7 - Distributed Programming 
- Introduction into Consensus Protocols
- Raft
- Implementing Raft with Go 
- <a href="docs/7.0-Distributed-Programming-Raft.pdf">Slides</a>
- <a href="docs/exercises/Exercise7.md">Exercise 7</a>

## Lecture 8 - Cross Compiling with WebAssembly 
- Introduction to WebAssembly
- WebAssembly implementation of Go
- <a href="docs/a.0-WebAssembly.pdf">Slides</a>
- <a href="docs/exercises/Exercisea.md">Exercise 7</a>
 