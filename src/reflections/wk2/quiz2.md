# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A set of statements used to solve a problem. They can be reused.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility - A class and the contained objects should only have one responsibility

Open/Closed - Software should be open for extension and, closed for modification

Liskov Substitution - The program should still run correctly if parent classes are replaced with subclasses

Interface Segregation - Multiple interfaces to meet different customer needs instead of having customers use interfaces they don't need

Dependency Inversion - High and low level modules should depend on abstractions, not each other. Abstractions shouldn't depend on details and details should depend on abstractions
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The index is 3. It's the fourth entry and indices start counting at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(x > y){
  console.log(hi!)
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
iterator. I would use ++ to increase by 1 each time.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. Index.html is the first file accessed
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, Boolean, Number, String, BigInt, Symbol, Object, Function, null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is defined as part of the method and receives the argument when the method is called. An argument is the value/expression given when calling the method. Method has parameters and takes arguments.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are stored on the stack and reference values are stored in the heap. Reference values store a pointer to the location where an object is stored in the variable. Primitives store the value directly in the variable.
```