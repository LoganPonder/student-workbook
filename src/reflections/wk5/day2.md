# Day 2 | W-5 MongoDb Relationships -

### Daily Project: 

## What are the three types of relationships?
One-To-One(1:1)
One-To-Many(1:N)
Many-To-Many(N:M)

## What are the benefits of the traditional linking of relationships instead of Embedding
Linking has an advantage to when the original data grows, or a portion of it grows... it wont grow/exceed the enitre data set. Because it is only a "link"/reference to that data. See below questions/challenge.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?


With a N:M relationship, while designing it you have to consider of which you are comparing the other to. If you are referencing a few categories to each book, you'll be find due to the fact that there are far less authors than there are books. If you do the inverse, you could have many many books attatched to each category.

