# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation: bundling data/methods to limit outside access.

Abstraction: Process of selecting only the relevant data to reveal

Inheritance: objects can acquire properties of another object

Polymorphism: allows us to use a class just like its parent

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
Encapsulation: bundling data/methods to limit outside access.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility- Classes should only have one responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
class - Defines the properties of a set of objects. For example, Dogs could be a class.

instance of class- The instantiation of a class. For example, Josie could be an instance of the Dog class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
They allow you to add custom functionality to basic built in operations to be performed on an object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It separates a web app into 3 components which separate the business logic and user interface code from each other. Allows multiple developers to work on different parts of the same code. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Controller - Takes input and sends commands to the model or view
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service - Keeps logic from multiple models in one place. Stores states, variables, and links. Contains all business logic.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Model - Contains the object schema. 
```

