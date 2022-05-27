# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, inheritance, and polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
function access() {
  let property = staff.name
  return property
}
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
A mechanic in object oriented programming that does not allow direct access to maybe some key components of an object that you don't want accessed. By the users of course. 
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility meaning functions and classes should only have one job. 
```
**5.** What's the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
the class you use to create what that object looks like and an instance is a particular object that you made using that blueprint. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
a js object that wraps an object/function and watches over it as well as changes the behavior of the existing object that it watches over. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
to divide program logic into 3 divisions, model, view, and controller. Allowing for ease of use and orientation when it comes to building big or bigger applications. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The name says it all. It is the controller of the video game which takes in info from the view and gives info to the service and the model.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
it disperses info an takes in info as needed on the server side. Its where I put a lot of the functions that the controller asks for.  
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The models job is to manage data and make up the way data is supposed to look like for example, templates and objects. 
```
