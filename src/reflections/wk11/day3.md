# SQL Injection
## What is SQL injection?
SQL injection is the malicious attempt to input SQL statements that can manipulate your database. It was first acknowledged in 1998 and continues to be a problem to this day.

## What are 3 methods SQL injection can be done by?
User Input: Often in forms, the front end allows users to input text and, if it's not sanitized, it can result in SQL being run in the back-end.
Modifying Cookies: Malware inject SQL into a database by manipulating cookies that the front-end processes.
Server Variables: HTTP headers and other server variables containing SQL can manipulate the database if those are not sanitized. 

## How can we detect and sanitize SQL injection attacks?
We can use tools like SQLmap, Havij, and SQLninja to test the safety of our code. We can protect our application by sanitizing our code and using tools such as Dapper.