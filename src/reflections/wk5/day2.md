# MongoDb Relationships
## What are the three types of relationships?
One-to-one: Relationship between two entities. For example: Customer and Address. Each customer has one address and each address has one customer. Embedding is preferred in a one-to-one relationship.

One-to-many: One entity has multiple relationships while the other can one be tied back to one of the former entity. For example, Make and Model of cars. The make can have multiple models but, the models only have one make. Bucketing is preferred for large amounts of data and where pagination is important. But, Linking and Embedding are still useful in smaller cases or when pagination is not important.

Many-to-many: Two entities can have multiple relationships between each other. For example, a book could have many authors and authors can write multiple books. 

## What are the benefits of the traditional linking of relationships instead of Embedding
Embedding has a maximum document size of 16mb. For larger datasets, linking avoids maxing out that storage. It is also easier to return paginated data.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it? 
Say we have books and genre. We could embed genres directly into books because there aren't that many genres. However, we would not want to embed books into genres since there are many more books and they are always changing. If you know there are several relationships, the Third Collection design can be most efficient. It holds foreign keys which link the data together.