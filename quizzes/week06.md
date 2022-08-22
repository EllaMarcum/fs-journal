# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
the place in a program where the execution of a program begins.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
component is a model and 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```

```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template></template> block is the HTML markup of the UI. It defines the structure.
The <script></script> block is where we maintain the data and logic for the template.
The <style></style> block contains the styling for the markup in the template block
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The “L” in SOLID is for Liskov Substitution Principle.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
 Modern single-page apps such as a Vue application can transition from page to page on the client-side (without requesting the server). Vue Router is the official library for page navigation in Vue applications.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The state represents parts of an Application that can change. Each component can have its State. The state is Mutable and It is local to the component only.s
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
adding a service to an application, that just means that you are going to create a JavaScript file that will export something.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue: Your root Vue component, which contains the entire application main.js: the entry point of the entire application's JavaScript code.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
the style tag
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
If you have a piece of state that should be shared by multiple instances, you can use reactive () to create a reactive object, and then import it into multiple components.
```