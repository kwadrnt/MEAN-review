# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> MEAN stack review

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

We want you to choose the best stack for your final project. Using a JavaScript framework like AngularJS has a host of benefits, but we want you to revisit it before deciding if it's right (or wrong) for you.  Returning to a technology you learned and used in the past can be difficult! Reviewing is likely to solidify your understanding and help you make connections to any frameworks you learned since.

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

### Before we start...
Open 5 tabs that will be helpful resources for talking about Angular and the MEAN stack.

#### Consider the following statement

*Ruby on Rails is superior to the MEAN stack because Ruby is a much more beautiful and feature-rich language than Javascript. Rails is designed to expedite development time because it has built in structures to facilitate CRUD and many other common web development tasks.*

Take two minutes to write down your reaction.

#### Now, consider the following statement

*The MEAN stack is better than Rails because it is all JavaScript, the native language of the web.
Node's built-in V8 JS engine makes the MEAN stack app far faster than a Ruby on
Rails app. Angular creates dynamic, single page apps which are more intuitive to write
than the `.erb` style templating of Rails apps.*

Take two minutes to write down your reaction.


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

- the MEAN stack [`tunely-angular` sprint 5 solutions branch](https://github.com/sf-wdi-37/tunely-angular/tree/solutions_sprint_5), sprint 5 solution

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


Once you've written something out, taken the key screenshots (`cmd`+`shift`+ `4`), and gathered all the info you want to show us, please put your responses in this [google doc](https://docs.google.com/document/d/1baHa1_1RNApMIPhK9GH4rOu2GwUYVsHEuSSSZcfN_OI/edit).

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

On the [google doc](https://docs.google.com/document/d/1baHa1_1RNApMIPhK9GH4rOu2GwUYVsHEuSSSZcfN_OI/edit), include at least two screen shots that display the evidence that your directives are functioning. Include two or more sentences explaining why these screenshots are evidence of the directives you selected.

## Terminology and Concepts

First, without resources, write your own working definition of each of these five concepts. In which files do they live? Why is it part of Angular?

* directives
* controllers
* templates
* services
* client-side routing

Now, with whatever resources you'd like, work with a partner to refine your definitions to build a more complete picture.

How did your original definitions match with your more refined definitions?

## Lab

Working in teams of 2 or 3, choose one of the three following ideas and build the Angular portion of it.

Follow this suggested "micro-sprint" structure:

1. Build a "first-draft" version of the view and connect it to a working controller. Ensure that variables in the controller can display on the page.
2. In the controller, create an empty object that the form inputs will `ng-model.` Make each input model a different attribute of that object.
3. Refine the form so that pressing the "submit" button executes some simple function that's defined in the controller. For example, it could build an object using the inputted data and console log that object.
4. Polish the form so that it's responsive to the user's input.  
5. Make that function into an `$http` call that makes hits a route on the server-side.
6. In server.js create the functionality at the server-side route that you're hitting.
7. Get the data to actually store in a database. You'll need to build a schema to enact this plan.

Please feel free to reference previous notes.

#### Payment form

Build a responsive payment form that looks somewhat like the following:

![image](https://cloud.githubusercontent.com/assets/6520345/23038703/d7630e4a-f43f-11e6-8fbc-3128d7aba220.png)

and has these features:

* While you're inputting values, the box around the form is red/orange. When your value is valid, the box around the form changes to be green.
* When I type the first 4 digits of the card number, the card company displays on the fake card image.
* As I type digits from my card, digits appear on the fake card image.
* As I type the expiration date, it appears on the fake card image.
* When I select the security code/CVC input box, the fake card image "flips over" and the digits I type appear on the back side of the card:

![image](https://cloud.githubusercontent.com/assets/6520345/23038881/7e597a18-f440-11e6-81bf-8657c1d5c61f.png)

#### Password Creation Widget

Build a responsive password entry widget that looks something like the following:

![image](https://cloud.githubusercontent.com/assets/6520345/23038960/b7c82920-f440-11e6-9332-7c230da918c2.png)

and has these features:

* Displays the password requirements and checks the boxes when the input satisfies those validations.
* Adds a checkmark within the input box when it satisfies all requirements.
* Has an orange/red color outline on the input while your password doesn't satisfy all of the requirements. The outline turns green only when all of the requirements are fulfilled
* A password confirmation box that behaves similarly. It has an orange/red color outline while it doesn't match and a green outline when it does match your original password.

#### Blog

Build a blog entry page that allows a user to make a title and a multi-paragraph entry. It should have the following features:

* Titles should be between 2 and 20 characters long.
* While you're title is invalid, the box around the form is outlined with red/orange. While your value is valid, the box around the form changes to be green.
* In the blog entry input box, pressing enter should create a new paragraph and *should not* submit the form.



## Additional Resources for Review
- the Angular [book app](https://github.com/sf-wdi-34/angular-services-training) and its solution branches.
- the Angular [Cards against Assembly](https://github.com/sf-wdi-34/angular-custom-directives) lab and its solution.
