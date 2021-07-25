# Async and Await
## What is the purpose of Async/Await?
It cleans up/builds upon promises.It allows you to add prepend 'await' to a function which tells the program to wait for this to finish before continuing.

## What must you do in order to await a promise inside of a function?
Call the function prepended with 'async'. Then, prepend the function within that with await. Surround this with a try catch so, the program has something to do on success and fail.

## What are some of the primary benefits of Async/Await?
It makes debugging easier. The debugger will not step over asynchronous code but, the compiler considers Async/Await as synchronous code.

[Pokedex](https://github.com/amanda-rice/pokedex)