## Function, methods and constructor calls

Functions are just functions. Methods are object properties that happen to be functions

Constructors are functions that become new objects (think classes). Constructors can be utilized by calling a new instance of it.

## High order functions

high order functions are nothing more than functions that are passed in functions and return a function

## Bind, Call and Apply

The bind() method creates a new function that, when called, has its this keyword set to the provided value
"A for array, C for comma"

Call and apply both function similarly like bind but call takes in many set arguments and apply takes in an array

## Arguments

Arguments is a key word that returns all the arguments passed into an function.  This can be very useful for instance arguments.length

## Generator function

Generator functions are functions that can return multiple values. Generator functions will have yield tags in its body and will iterate through each yield and resolve each in order until everything has been resolved.  Once a yield has been resolved it cannot be resolved again.

Generator functions have the syntax function *().  Everytime it spots a yield it will 'yield' the result to the generator have it figure out what it is then return to the spot of the original yield.

## Stateful vs. Stateless

A state- less API provides functions or methods whose behavior depends only on their inputs, not on the changing state of the program.

## What's the use of 'use strict' in js

Code errors that would have failed silently will no longer do that.  It will pick up on undefined 'this', prevent global variables and various other things

## How can you reliably test if a value is equal to NaN?

A better solution would either be to use value !== value, which would only produce true if the value is equal to NaN.

## What is a closure

A closure is an inner function that has access to the variables in the outer (enclosing) function’s scope chain. The closure has access to variables in three scopes; specifically: (1) variable in its own scope, (2) variables in the enclosing function’s scope, and (3) global variables.

## What does 1 && 2 return?
&& returns true or the value of the second value

## What is the output out of the following code? Explain your answer.
var a={},
b={key:'b'},
c={key:'c'};
a[b]=123;
a[c]=456;
console.log(a[b]) = 456;
