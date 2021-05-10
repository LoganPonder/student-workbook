# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package.json file is what is used to store all relevant npm packages associated with the dependencies of an application.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json file needs to go at the root level, so that the folders/files that come after can rely on the dependencies and packages listed therein. 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
vue.min.js
```
**4.** ___.env____ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
The '.env' file
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
heroku logs
heroku logs --source app

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
With your git repository connected to Heroku, you just need to commit and pus the changes to the heroku master, or 'Deploy to Heroku' button via GitHub
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
By branching off the main version you can prevent a team from shipping bad code. If all changes were pushed to the main right away, there could be multiple merge conflicts or bad code. Branching provides a better alternative/saftey net.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen during testing/checks(or just after) before the code is merged with the main branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
