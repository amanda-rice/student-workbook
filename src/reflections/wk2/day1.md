# Read Intro to JS > Var, let and const and answer the following questions
## What is Scope ?

Where variables can be used. Var's can be globally when declared outside of a function or locally scoped when declared inside of a function which means that it can only be accessed inside that function. 

## What is Hoisting ?

Hoisting in JavaScript is when function and variable declarations are relocated to the top of their scope before execution. This can lead to bugs if the same variable name is used more than once in the code.

## In what cases might you use let vs const vs var?

Let - currently the preferred variable declaration. It is block scoped so, it's only available within the curly braces it resides. It can also be updated but not re-declared in the same scope. Not initialized automatically.

Var - initialized as undefined. Hoisted to the top of it's scope. Var would be used if you need function scoping instead of block scoping.

Const - maintain constant variables. They are block scoped like let declarations. Const variables cannot be changed or re-declared. Hoisted to the top but, not initialized. These would be used if you have a value that needs to be used throughout an application and will not be changing. It takes away the risk of accidentally updating the value.