# JavaScript Promises
## What are the three states of a Promise?
- Pending: Before the promise has failed or resolved
- Resolved: a promise that completed
- Rejected: a promised that has failed

## How do promises seek to resolve the issues of "callback hell"?
When there are multiple async operations, promises can be chained which cleans up the code. It allows for multiple then statements in a row followed at the end by one catch.

## What is the difference between .then() and .catch()?
- Then() is called if the Promise is resolved.
- Catch() is called if the Promise is rejected. 


[Greg's List-API](https://amanda-rice.github.io/gregs-list-jobs-houses/)