# Encapsulation in Javascript
## What is the purpose of Encapsulation?
It prevents access of data from the outside. Only the object's methods that call the state have access to it.

## What were some of the problems with closures and the underscore prefix?
The underscore prefix doesn't actually do anything. It's just a naming convention and, if the developer working on them doesn't understand what they mean, they may allow the user to access them. They also increase the 'attack surface' for hackers. If something only needs to be used internally, there is no reason to risk exposing it to users.

## How do we create private variables in a ES6 Class? Why would you do this?
Create a variable inside a constructor function scope. It is private to the outside. Then, create function within the same scope that are privileged and manipulate private variable and return them to they can be run from the outside. 



[Vending Machine](https://github.com/amanda-rice/vending-machine)