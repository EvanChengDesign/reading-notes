# **Reading Notes | 04 APR 2024**

# Class 009

### *Bookmarks:*  
[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)  
[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
## **Questions & Answers**  

## What is functional programming?

Functional programming is a programming paradigm where programs are constructed by applying and composing functions. It emphasizes the use of pure functions and avoiding shared state, mutable data, and side-effects.

## What is a pure function and how do we know if something is a pure function?

A pure function is a function that, given the same input, will always return the same output and does not have any observable side effects. We know something is a pure function if it consistently yields the same result for the same input and does not interact with or modify anything outside its scope.

## What are the benefits of a pure function?

The benefits of a pure function include easier testing and debugging, improved code readability, and the ability to reuse code. Pure functions also facilitate parallel processing and lazy evaluation, leading to potentially optimized and more efficient code.

## What is immutability?

Immutability is a principle in programming where an object cannot be modified after it has been created. Instead of changing the original object, you create and work with new objects that are versions of the original.

## What is Referential transparency?

Referential transparency is a property of expressions in programming where an expression can be replaced with its value without changing the program's behavior. This concept is closely related to pure functions and immutability.

## What is a module?

A module is a discrete unit of code that can be separately developed and maintained, and which can be reused in different parts of a program. Modules help in breaking down large programs into small, manageable, and reusable components.

## What does the word ‘require’ do?

The word ‘require’ is used in some programming languages, like Node.js, to include modules into a file. It loads the module's contents, making its functions and objects available to the current file.

## How do we bring another module into the file the we are working in?

To bring another module into the file we are working in, we use the `require` function in Node.js or the `import` statement in ES6 syntax, specifying the path to the module.

## What do we have to do to make a module available?

To make a module available, we must export it from the file in which it is defined. This can be done using `module.exports` in Node.js or the `export` keyword in ES6, allowing it to be imported or required by other files.
