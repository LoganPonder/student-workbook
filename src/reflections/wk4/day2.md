# Day 2 - W4 API/Promises

### Daily Project: https://github.com/LoganPonder/spring21-gregslist-mvc

### What are the three states of a Promise?
**Pending:** Initial State, before the Promise succeeds or fails 

**Resolved:** Completed Promise

**Rejected:** Failed Promise

### How do promises seek to resolve the issues of "callback hell"?
Promises allow for a cleaner syntax, allowing us to chain them together as opposed to continually passing callbacks as arguments for eachother.

### What is the difference between .then() and .catch()?
.then() runs when a promis returns successfull. .then() will execute when some type of condition is met.... .catch() runs when there is some sort of error. 