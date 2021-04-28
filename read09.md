# Concepts of Functional Programming in Javascript

### What is functional programming?

Functional programming is a programming paradigm a style of building the structure and elements of computer programs  that treat computation as the evaluation of mathematical functions and avoids changing state and mutable data. 

## pure functions

The first fundamental concept we learn when we want to understand functional programming is pure functions.

* It returns the same result if, given the same arguments (it is also referred to as deterministic), It does not cause any observable side effects

* If our function reads external files, it’s not a pure function — the file’s contents can change

* Any function that relies on a random number generator cannot be pure.

* It does not cause any observable side effects  .
Examples of observable side effects include modifying a global object or a parameter passed by reference.


### Pure functions benefits

* Immutability

Unchanging over time or unable to be changed.
When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.


### Refactoring JavaScript 

some straightforward to implement methods that can lead to easier-to-read code. 

* Cache variables 

* Check for Web APIs before implementing your own functionality