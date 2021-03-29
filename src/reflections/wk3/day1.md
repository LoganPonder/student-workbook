# Day 1 / W3 - Advancing with JS/Modules

## Project: https://github.com/LoganPonder/zoo

### What problem does using exports solve?
Exports allow us to expose public variables, functions, and classes. Protecting sensitive parts of our program, and exposing others. Combining multiple script files, into one html script tag.

### How does export differ from export default?
Default is reserved for exporting a single object out of a file. While export(without 'default') can be used to export multiple ojects our of a single file.

### What is a benefit of using the Module System?
The Module system allows our code to be  broken down into smaller contained files. Script tags can be referenced in one tag, via export/import processes. Debugging also becomes easier due to the fact that we can pinpoint exactly where/and in what file the error/functionality occurs.