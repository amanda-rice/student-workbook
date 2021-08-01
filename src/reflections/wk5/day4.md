# MongoDb Relationships
## What is a virtual property?
The virtual properties are additional functions that return data using the schema fields. For example, they can concatenate first and last names and return a full name.

## When might you use a virtual property?
Getting the full name of a person. This way, you only have to write the concatenation once and it can be re-used for all people.

## How do you search by a virtual properties value?
You can't create a document query with a virtual property. You can find the virtual property's value by calling the object.'virtual property name'.