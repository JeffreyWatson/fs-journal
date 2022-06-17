# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
main.js
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
a page is what will display all of you content that you are wanting rendered. The component is simply a element inside that page that can be reused if necessary for any page.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for="a in apples" :key"a.id" :apple="a"
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template></template> || <script></script> || <style></style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle = States that objects of bigger classes should be replaceable with objects of smaller classes without breaking the application.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
<router-view></router-view>
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
I have no idea and need help understanding this. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
To make calls to the api using the crud methods and updating the appstate.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
<style scoped>
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
watchEffect
```