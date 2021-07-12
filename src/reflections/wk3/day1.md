# Read Asynchronous Code > Callback Hell and answer the following questions
## What are some of the signs and causes of Callback Hell?
An obvious sign is long, pyramid shaped the code. It's often caused by developers not understanding the order tasks execute in a program.

## What does the asynchronous mean and how are callbacks involved?
Asynchronous means 'takes time'. Callbacks are usually used when talking to databases and downloading. We know these will take longer than other processes so, we come back to them and run the callbacks when they finish.

## Summarize the 3 ways to avoid / fix Callback Hell
Write Shallow Code:
- Name functions: Gives stacktraces when you get exceptions. Increases readability of code. Functions can be moved.

Modularize:
- Write modules that only do one thing and group them into bigger modules

Handle all errors:
- Makes your code stable.
- Always plan on errors happening so they're more easy to debug when they do happen.

[Zoo - Objects](https://github.com/amanda-rice/zoo.git)