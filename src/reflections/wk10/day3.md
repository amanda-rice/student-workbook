# Welcome to SQL

## In a SQL table, what is the difference between information in a row and information in a column?
Each column is a category of data to be input. The rows are individual records that include data for each column.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters(
  id int NOT NULL,
  name VARCHAR(255) NOT NULL,
  age VARCHAR(3) NOT NULL,
  description VARCHAR(255) NOT NULL
);

## What is the difference between the following statements:
DELETE FROM table_name: deletes rows from table_name

DROP TABLE table_name: deletes the table table_name


[Castles](https://github.com/amanda-rice/castles)
