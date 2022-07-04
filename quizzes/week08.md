# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It is one of the most important files that keeps a node project running. It contains metadata that is required before publishing to NPM. It also defines functional attributes of a project that NPM uses to install dependencies, run scripts, and identify entry points.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
At the root of the file and because it needs to be implemented from the beginning of your code.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
The bundling command.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Connection strings
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
The Heroku CLI, the dashboard, your logging add-on, or in your log drain. 
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone the repository from GitHub to your local device, Make your changes, and commit them to GitHub. Log in to your heroku app, set remote for your project. Then push to heroku master to deploy updates. 

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Simply because you will typically be working with several devs and at that point having a branching system implemented will make for better organization.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
After automated checks have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```