# Day-3 | W5 MongoDb Relationships

## Daily Project: https://github.com/LoganPonder/space-server

### In simple terms what is a sub-document?
A sub-document is a document that is nesteded inside another document.(similar to nested objects/arrays)

### When might you use a sub-document?
When you want to store a set of values to a single property. A single value could have multiple properties, and inside the properties the value could be a sub-document, or a set of additional values. Similar to a character, its abilities, and the details of those abilities.

### How do you add to a collection of sub-documents? What about editing them?
Similar to working with normal javascript objects. After finding the piece of data that you need to manipulate, you can access those specific object's properties and reassign the values, or add additional values to a specific property/array. Once those sub-documents are added, they can be saved/updated as the original document.