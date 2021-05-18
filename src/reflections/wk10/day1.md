# Day 1 - W10

### Daily Project: https://github.com/LoganPonder/cSharp-rock-paper-scissors

## What are the three categories of data types? How are they different?
Value, Reference, Pointer data types. That are different in the way in which stores them in memory.

## What are the Value-type data types? What differences do you notice from JavaScript?
Value types hold data within their own memory space, similar to primitive data types in Javascript. And just like in JS if you pass them through other functions their value doesn't change as they each have their own spot in memory.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
Reference data types in C# are stored not by the value they hold, but by the place in memory in which they are stored. As in JS reference types that are store on the heap, reference types in C# will change value if they are mutated since you are not adjusting that single var, but the place in memory that potentially multiple pieces of data are pointing to.