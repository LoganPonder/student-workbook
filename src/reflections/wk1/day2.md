# Day 2 - Html/Css

What I learned today...

Daily Challenge:
https://github.com/LoganPonder/cool-site
 https://loganponder.github.io/cool-site/.

### 1. What is a Pseudo-Class and what are some of the most common ones you think you will use

A Pseudo-Class is a keyword/class that is added to the end of an element in CSS, describing the 'state' of a certain element within an application. For example, the most common one I have used is the :hover Pseudo-Class. When a certain element is hovered over by a user, it could do something as simple as changing the cursor to pointer; or it could trigger some sort of function/interactive user experience.


### 2. What is Specificity and how might you use it to your benefit?

Specificity in CSS allows developers to target different elements at varying degrees of specificity(as the name implies) in order to apply detailed styling throughout an application. Each element has a different 'value' depending on the id's, classes, elements(ect...) that are attached to it. This allows developers to have total control over not only the general layout, but specific elements within an application by manipulating these 'values'. For example, assigning a unique ID to a specific element would take precedence over a previously declared 'class' style, due to the fact that the value of the ID is greater than the value of the class.
 
### 3. What problems do you think you could run into if you over-utilized the !important feature?

The !important feature overrides all previously stated CSS rules for a specific element, disregarding the 'specificity calculations'. The overuse of this feature could cause problems when there are 1,000's of lines a code, and you're trying to figure out why a specific property isn't being applied. It's easy to add this feature, but forget where and how many times it has been added. It's much better to fully understand how specificity works, and utilize the given values as they were intended. It's considered best-practice to avoid the use of the !important feature!

***-Logan***