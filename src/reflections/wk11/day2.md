# Relationships
## What is the difference between a primary key and a foreign key
Primary keys are unique (and cannot be null) in a table and identify each unique row. When a primary key is being used as a reference in another table, it's called a Foreign Key. It tell that table where to look in the 'foreign' table for the relationship.

## What is an Alias?
It's a way to rename a property in the output. This is often used when joining tables with properties that have the same name such as ID.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

SELECT
        d.*,
        p.*,
        dp.id
      FROM doctorPatients dp
      JOIN patients p ON p.id = dp.patientId
      WHERE d.id = @doctorId;
      ";

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorPatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

[Bloggr](https://github.com/amanda-rice/blogger)