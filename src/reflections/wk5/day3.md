# Mongoose 101
## In simple terms what is a sub-document?
They are documents that are stored inside other documents. They are called embedded documents in MongoDB.

## When might you use a sub-document?
If you are storing data for a 1:1 relationship, you can use the sub-document to directly embed that information. Also, they could be used for 1:many relationships and you could use an array of sub-documents to store the many records.

## How do you add to a collection of sub-documents? What about editing them?
You can create a nested object and pass it into a new Model or create an object and then edit the object to add new sub-documents. To update, you can use findOne to find that document. Then, change that array and save it.