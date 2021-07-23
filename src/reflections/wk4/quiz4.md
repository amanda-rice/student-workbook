# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
synchronous - code is executed one-by-one in the order it's written until the task's completed. Must get previous task must complete before next can start running.

asynchronous - code can continue running while the asynchronous code tries to run.

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
Code that waits for events to occur and responds when they do. Common examples include onclick, onload, and onmouseover.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed Principle. Modules should not be open for modification and should be open for extension
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A function that is passed in another function as an argument
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is an object that says we will do something in the future if our code runs successfully. We capture errors with a then/catch statement where we capture the error in the catch. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, put, and post.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Organizing data with methods that access it and restricting access from the outside. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Messages in the 200s
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
"Internal Server Error" It's catch-all response that often indicates the server couldn't find a better error code.
```