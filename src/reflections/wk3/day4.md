# Day-4 | W3 - Proxy Objects

## Daily Project: https://github.com/LoganPonder/darryl-store

### What problems does the Observer Pattern seek to solve?
The Observer Pattern allows a program to essentially "listen" for changes in the state, often triggered by a user, and update things on the DOM based upon some of those changes. A "one-to-many" relationship, where when one state changes, a series of changes could occur automatically. A class holds an array of observers to watch, and what methods should be triggered.

### What are the three mechanisms of the observer pattern?
Subscribe: adds a new observable events

Unsubscribe: removes observable events

Broadcast: executes all events with attatched data

### Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

Our BCW templates, and the MVC pattern we have been using relies on the fact on our State being changed. Throughout our code, we are listenting for "changes" within our ProxyState.on('item', _draw). When we do "observe" a change in data, our _draw() function is automatically triggered, re-rendering the page.