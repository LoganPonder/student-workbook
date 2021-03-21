# Day 1 / W2 - Intro to JavaScript

Daily Journal....

### What is Scope ?
Scope is essentially the "visibility" of variables within a program. And how/where those variables can be accessed.

### What is Hoisting?
Hoisting has to do with how JavaScript interprets our variables/functions prior to actually reading the line of code. 'Let' is hoisted to the top of the page, and it's value is initialized with undefined. While 'let' and 'constant' are hoisted but are not initialized. Function declarations are hoisted to the 'top' of the page and their functionality is accessible even before that line of code is reached.

### In what cases might you use let vs const vs var?
With the addition of let and const, 'var' isn't considered 'best practice' due to the fact that it's value can very easily be reassigned without knowing. 'Let' is good for declaring a variable that might be changed throughout the duration of a program or function's execution context. 'const' can be used for more "concrete" variables that you don't want to change, for example an object.