# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Where the function is written in code, along with its functionality. It's not usually invoked at this time, just "defined".
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single-responsiblity Principle
O - Open-closed Principle
L - Liskov Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2 - because arrays are zero indexed.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you['friends'] = them;
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(a > b) {
  return true;
} else {
  return false
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOCUMENT OBJECT MODEL - index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
- undefined 
- boolean 
- number
- string
- bigint
- symbol
- object
- function 
- null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the placeholders that are passed in when a function is defined. Arguments are what are passed in when a function is invoked, with specific values.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
It has to do with how and where they are stored. Primitive values are stored on the stack, and each have their own unique place in memory. While reference value's are stored "by reference" on the heap allowing their value's to be mutated, potentially sending a "ripple effect" throughout a program, intentionally/unintentionally.
```