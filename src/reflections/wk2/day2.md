# Day 2 - JS Functions

### What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

Function Declarations are hoisted and their functionality is avaiable to use; while function expressions are not. Arrow functions came with ES6, are are a cleaner/more streamlined way of writing functions

Function Declaration: 

    function greet(name) {
    
    }

Function Expression: 

    let greet = function(name) {

    }

Arrow Function:

    let greet = (name) => {

    }

### What is the difference between Parameters and Arguments?
Parameters are placeholders for when a function is defined. Arguments are what are passed into the function when it is invoked(taking the place of the parameter placeholders).

### What are higher order functions? Can you provide an example?

A higher order function is a function that takes in another function as one of it's arguments.

    function legday() {
        console.log('Lets train legs!');
    }

    function armday() {
        console.log('Lets train arms!');
    }

    function exercise(type, armday, legday) {
        if(type === 'arms') {
            armday();
        } else if(type === 'legs') {
            legday();
        }
    }

    exercise('legs', armday, legday);