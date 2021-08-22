# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file can have a lot or a little in it. It's a central repository for configuration and metadata information. It includes the name and version fields which are the most important fields if you are publishing your package. These two fields create a unique identifier. It also includes a description and keywords so it can be found in npm. Other fields include homepage, bugs, license, people, funding, bin, etc.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
It is in the root of the project for both the client and the server so it can be easily found.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
The Activity tab or clicking the more drop-down in teh app on your Heroku dashboard.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Have heroku automatically update when your production branch changes.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
If you make a mistake and already pushed to GitHub, it isn't necessarily in production yet. Also, if you have an app that updates when production does, you won't push anything to that production branch until it's 100% ready and you can store the working version in a different branch.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
It should happen during the Sprint Review
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merge
```
