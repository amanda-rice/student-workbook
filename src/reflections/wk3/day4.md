# Read Advancing with JS > The Observer Pattern and answer the following questions
## What problems does the Observer Pattern seek to solve?
It prevents the application from having to run functions manually every time something on the page needs to be updated. It allows multiple elements to stay synced.

## What are the three mechanisms of the observer pattern?
Subscribe: adds observable event

Unsubscribe: removes observable event

Broadcast: executes events with attached methods

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
We use proxy objects to make a copy of the state that the user can manipulate so they don't have direct access to the state. Then, we set up observers for when the proxy objects are updated and use them to update the user interface.

[Fruit Stand](https://github.com/VeronicaBlake/fruitStand)