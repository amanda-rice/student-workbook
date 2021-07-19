# Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions
## What are the two common operations that we will set in the handler?
Get and trap. The handler has a set of traps that are activated when an object property is accessed.

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?
You have to call the proxy object and the property you want to access. For example: proxyObj.name . Otherwise, you will get undefined.

## What are some of the benefits of the proxy object that we are using in our structure for applications?
They keep the user from directly manipulating the state. Instead, they get a copy of the state to manipulate how they want. Also, you can set properties to private so they can't be accessed.

[Greg's List](https://github.com/amanda-rice/gregs-list-jobs-houses)