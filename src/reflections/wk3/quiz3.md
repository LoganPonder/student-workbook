# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction
Encapsulation
Inheritance
Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation bundles like data and methods within a class. Not only grouping this data together, but essentially 'hiding' it from clients that might intentionally/unintentionally alter that data.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the original class that is defined by the user, with a constructor and methods(encapsulated within the class). An instance of a class is a object that is created using that class template, not the orginal class definition. There can be multiple class instances, but only one class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is an object that wraps, or acts as a interface/copy for another object in memory. It limits access to the original object it's 'protecting', shielding the sensitive data from those who don't have access. A proxy object can also add additional functionality for that object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC design pattern seperates a program into three logical sections, structuring how input is received from a user, processed/stored, and rendered back to the user.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is the point of contact for the View. Its receives the input from the user and passes it onto the Service. The Controller also contains the _draw() functions and other things related to "rendering" the user interface.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service contains the logic for a program. It takes info from the controller and decides how/what to do with it. It communicates with the State/Model to save data, or retrieve data and push it back to the View/controller so that that data/logic can be rendered for the user.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model/state is where our data is stored. This is often accessed via a Proxy Object in order to protect sensitve data. The Model communicats with the controller/service to recive and send data to the user.
```

