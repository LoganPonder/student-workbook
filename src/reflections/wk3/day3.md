# Day-3 | W3 - Proxy Objects

## Daily Project: https://github.com/LoganPonder/spring21-gregslist

### What are the two common operations that we will set in the handler?
Get & Set

### What do you have to make sure you are doing with every Get to insure the value does not become undefined?
You have to make sure that you are returning a value.

### What are some of the benefits of the proxy object that we are using in our structure for applications?
Proxy objects allow us to add some basic logic into our get/set traps. We can see if certain conditionals are met, and then return or not return a value associated with that particular object. We can essentially create private properties within that object with the same kind of "trap logic" therefore hiding access to certain properties.