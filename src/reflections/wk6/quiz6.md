# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create 'project-name'
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
package.json has a list of the scripts
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for.... utlizing props
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
template, script, style
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov substitution principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
In our <script> tags we use router-links to connect to another page, specified by a specific name within our routes/path/name/component page
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
There is one 'AppState' for a project, the state within a give object is scoped to that specific component. In vue, we use the 'computed' feature to "watch" data in AppState, and update it accordingly.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services serve as our 'logic'. We kick things to service to talk to our api's, sending and receiving the data we need.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue
```
**11.** The ___style/*___ tag is used to alter the styling of your entire Vue project.  Adding the ___scoped___ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```

```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
computed()
```