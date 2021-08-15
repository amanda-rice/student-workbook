# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
You can either use double curly braces around a variable to bind or a colon in front of an HTML attribute
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Loads most of the resources only once which makes it faster than Multi-Page Apps. More mobile friendly. Backend code is reusable.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Runs that method when the page loads.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
It's used to update props. We use it when we want to submit a form. All values entered get saved in the state if they have v-model.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
It's used as an event listener. For example. v-on:click
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-show, v-if, v-else
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
Allows you to differentiate between input in v-if vs v-else. Inputs are rendered from scratch when you toggle between the if/else
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
They help show content. You can v-bind the tag you want to print and then, its children are printed at the slot tags
```