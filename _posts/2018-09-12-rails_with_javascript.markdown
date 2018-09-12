---
layout: post
title:      "Rails with JavaScript"
date:       2018-09-12 14:17:20 -0400
permalink:  rails_with_javascript
---


My last project was based on Ruby on Rails which was a “recipe app” which used MVC architecture and restful convention. So in our last project we learned about the rails magic. 
Without further ado let’s talk about the current project. This project is mainly based on JavaScript. JavaScript allows us to dynamically add content to user interface without reloading the page just the part of the page is updated instead of the entire page. JQuery is a JavaScript library used by developer regardless of the language or framework used. The exciting thing about this project is that we didn’t have to start from scratch instead add JQuery features to the previous Rails app.
I listed all the requirements for this project and tried to figure out how to incorporate them in my existing Rails app. Initially I felt overwhelmed and challenged but ultimately manage to figure out and was able to add new features in my previous project. I created recipe, ingredient, comment and recipe_ingredient serializers, also created JS libraries for the same and then started added the code for the new features in these libraries and met following requirements. 

### *Include a show resource rendered using jQuery and an Active Model Serialization JSON backend.*

*On (view/ingredients/show.html.erb) e.g /ingredients/1 we are using “Next Ingredient <<” and “ >> Previous Ingredient” buttons to sift through the ingredients and display recipes associated with that ingredient using ingredients.js file e.g while on ingredients/3 show page if you click “Next Ingredient <<” button you will navigate to ingredients/4 and if you click “>> Previous Ingredient” button you will navigate to ingredients/2* 

### *Include an index resource rendered using jQuery and an Active Model Serialization JSON backend.*

*On / index page we have "Read More" link, when clicked will append  entire description, link will change to "Read Less" and when this is clicked it will append only 30 characters to description
On user's /recipes index page we again have "Read More" link, when clicked will append  entire description, link will change to "Read Less" and when this is clicked it will append only 30 characters to description.*

### *Include at least one has_many relationships in information rendered via JSON and appended to the DOM.*

*Recipe has many comments new form on recipe show page is rendered without page refresh and appended to the DOM.*

### *Use your Rails API and a form to create a resource and render the response without a page refresh.*

*On e.g. recipe/1 show page new comment is created by submiting a comment form. Then new comment is appended to the DOM without page refresh.*

### *Translate JSON responses into js model objects.*

*When comment form is submitted on recipe/1 show page, the comment's id, content, recipe_id and user of new comment is used to create a JS comment object.*

### *At least one of the js model objects must have at least one method added by your code to the prototype.*

*The data of a comment is passed into the createCommentsDiv() comment’s prototype function to create a “DIV” and then “DIV” is appended to the DOM.
The form input fields are cleared by clearFormFields() comment’s prototype function.*
.
