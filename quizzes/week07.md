# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
{{This is one way to bind data in vue.}} also inside of an html attribute you can use the v-bind and for an image it is :src.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single page application.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Overall speed of the application. An mpa can send multiple server requests whereas a spa is structured to not have to do that as often. The ux can be better structured or more mainstream of what we see nowadays and what is more comfortable. 
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is a lifecycle hook that actively sets up the page, where onMounted is applied, immediately upon rendering.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
It is used for updating a form or input types of that nature and will ignore any initial value that was set to begin with and allow you to change that in the applications. It can be used when updating a form that was already filled out that you may want to edit down the road. Say a profile page for instance. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
V on can be used to create multiple bindings of the same directive in a single attribute. the @ symbol is just shorthand for v:on and can be used from what i have seen for @clicks for buttons. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
V-if. When using this directive, the elements will only be rendered when the condition of the v-if returns a truthy value. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute is just a way for vue to better identify the differences of the objects that it is sifting through, one that makes each object unique. Usually an id. 
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slots allow you to structure components throughout your app in a cool and efficient way. Simply by adding a slot and giving the class the name of a the component that you have made beforehand.
```