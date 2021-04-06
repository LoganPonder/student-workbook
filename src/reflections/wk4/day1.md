# Day 1 | W4 ASYNC/CALLBACKS

## Daily Project: https://github.com/LoganPonder/trivia-api

### What are some of the signs and causes of Callback Hell?
Callback Hell is often created when devs try to create code that reads 'top down' sequentially.  Signs of Callback Hell include a pyramid look to one's code, as well as a bunch of '})' at the end of code.

### What does the asynchronous mean and how are callbacks involved?
Javascript's thread of execution allows for one thing to happen at a time, inherently JS is synchronous. Asynchronous code allows JS to essentially "branch off" and retrieve data, while the rest of the program continues to run. Therefore avoiding any "blocking" of code that might occur when retrieving/receiving data from an external source. Callbacks are often used with ASYNC code as they are used as parameters(higher order functions) in other functions. Callbacks don't return something right away, they often execute once certain data is received.

### Summarize the 3 ways to avoid / fix Callback Hell

1.) Keep Code Shallow: use proper naming conventions and put function declarations at the bottom of the page(made available by hoisting).

2.) Modularize: creating smaller 'libraries' allows for code to be more concise, and easier to understand/debug. This also helps avoid the 'pyramid effect' associated with Callback Hell.

3.) Handle Every Single Error: Since callbacks occur in the 'background' of a program, it's important to take into consideration any errors that could occur with each instance of a callback. 