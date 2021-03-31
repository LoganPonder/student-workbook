# Day-2 | W3 - Encapsulation

## Day-2 Vending Machine: https://github.com/LoganPonder/vending-machine

### What is the purpose of Encapsulation?
Encapsulation groups data and their related methods inside a class. This prevents unauthorized/unintentionally access, in turn "protecting" the state/data of an application.

### What were some of the problems with closures and the underscore prefix?
For one, the underscore convention is not adapted by all. Less experienced devs might not know about this convention and attempt to change/use the function, causing the code to break.

### How do we create private variables in a ES6 Class? Why would you do this?
Private variables created inside a class essentially "protect" them from being mutated. 
In order to access or use them, one must access first the class and then the methods on that class, where in lies the private variable. Due to the fact that the methods and private variables are lexically scoped together.