# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> MEAN stack review

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

Remember Angular?  How does it fit in with an express back end? What if you want to build a MEAN app for project 3?  Let's hit refresh on some skills and knowledge. 

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- Explain how to use an Angular front end with a MEN back end. 
- Explain basic Angular setup and write examples of important built-in directives.
- Identify key Angular concepts: directives, controllers, templates, services, client-side routing.

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

- Build a full application in MEN, MEAN, and Ruby on Rails stacks.
- Locate course materials to help use technologies we haven't talked about in a long time.
- Give a detailed walkthrough of a MEN stack application.



## MEAN

* What does MEAN mean?   
* How is it different from MEN?  
* Why do we use the MEAN stack?

### What is AngularJS?

From the [Angular Guide Introduction](https://docs.angularjs.org/guide/introduction):

* A "framework for dynamic web apps"
* "Lets you use HTML as your template language" and helps you "extend HTML's syntax"
* "Handles all of the DOM and AJAX glue code you once wrote by hand and puts it in a well-defined structure"
* Is "opinionated about how a CRUD application should be built"
* Comes with "Data-binding, basic templating directives, form validation, routing, deep-linking, reusable components and dependency injection"
* "Angular simplifies application development by presenting a higher level of abstraction to the developer"
* "Not every app is a good fit for Angular. Angular was built with the CRUD application in mind."



# `tunely-angular` app

Let's review:

- the MEAN stack [`tunely-angular` sprint 5 solutions branch](https://github.com/sf-wdi-31/tunely-angular/tree/solutions_sprint_5), sprint 5 solution
- the Angular [book app](https://github.com/sf-wdi-31/angular-services-training) and its solution branches
- the Angular [Cards against Assembly](https://github.com/sf-wdi-31/angular-custom-directives) and its solution


This is a fully functional MEAN stack app.You'll be assigned a piece from within this list:

* public/scripts/app.js

* public/scripts/controllers/AlbumsIndexController.js

* public/scripts/controllers/AlbumsShowController.js

* views/templates

* views/index.html

* server.js

* package.json and bower.json

* Bounty: AJAX call

* Bounty: client-side routing

* Bounty: dependency injection

* Bounty: custom directive

* Bounty: service


Let's investigate these pieces and answer the following questions:

1. Is this server-side code or client side code? How do you know?
1. What parts of the MEAN stack does this represent? What technologies are present here (HTML, CSS, middleware, JavaScript, etc.)?
1. What is this piece of the application (file or directory) responsible for?
1. If this file was also in the non-Angular version, which parts are specific to Angular?
1. What lines of code are most important for understanding how this works?
1. What 3-5 lines of code are difficult to understand at first glance? After a closer look, what does that code do?


Once you've written something out, taken the key screenshots (`cmd`+`shift`+ `4`), and gathered all the info you want to show us, please put your responses in this [google doc](https://docs.google.com/document/d/18GLWllJ8iatxnCe3fH1ixC7bKTTm0esmNm_mRjz9ZDg/edit?usp=sharing). 

We'll each present 2-5 minutes on the piece we investigated to refresh the class on what it does... **BUT** this time we encourage you to engage an extra part of your brain as you explain. Drawing something, act something out, or invent a rhyme or jingle!



### Writing Angular

#### What is a directive?

Write a page to perform an example of two of the following angular directives.

* `ng-repeat`
* `ng-show` and/or `ng-hide`
* `ng-model`
* `ng-click`
* `ng-submit`
* `ng-href`
* `ng-src`

[Reviewing `tunely-angular` sprint 1](https://github.com/SF-WDI-31/tunely-angular/blob/master/docs/sprint1.md) may help to get your example set up.

On the [google doc](https://docs.google.com/document/d/18GLWllJ8iatxnCe3fH1ixC7bKTTm0esmNm_mRjz9ZDg/edit?usp=sharing), include at least two screen shots that display the evidence that your directives are functioning. Include two or more sentences explaining why these screenshots are evidence of the directives you selected.


## Lab

Working in teams of 3, choose one of your demos that might benefit from a database. Get it running as a MEAN stack app. That is, at least serve the `index.html` file and any stylesheets, client-side scripts, or images from your own Express server.  When you have it running, add a breif readme that lists all the contributors and push it to GitHub. 

Please feel free to reference previous notes.   
