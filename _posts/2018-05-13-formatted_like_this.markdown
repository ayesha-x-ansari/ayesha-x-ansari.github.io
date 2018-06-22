---
layout: post
title:      "Sinatra Portfolio Project:"
date:       2018-05-13 18:45:24 -0400
permalink:  formatted_like_this
---


I am trying to wrap up my Sinatra project. I still need to write this blog as well as to do a video demonstration of my app. We are required to use Sinatra for this Project. As we all know Sinatra is a light weight frame work, unlike rails which is a full stack web development framework that provides functionality for both front and back end web development. We are also required to use a Model-View-Controller paradigm which separates code by function.

Model – is responsible for logic

View – is responsible for rendering a web page to a browser

Controller – is responsible for relaying data from a browser to a web application and vice versa.

Also we need to use CRUD (create, read, update, delete) functionality using active record.

I considered a few ideas for my project but ultimately decided to code an app where authors can register and add their books on this site.

I was initially overwhelmed by the requirement of the project , and at the same time excited about using my newly acquired skill to practical use. I came across a few roadblocks but was able to overcome them. One of challenges I faced was how to prevent a category from being deleted when that particular category was already assigned to an existing book. Another one was how to keep count of user's attempt to logon and on third attempt to redirect to reset password page. 

My project has a basic login, logout, signup and reset password functionality. This app allows an author to register on this site.  Once registered he/she can add their books so that  it will show up on the author’s page and also on the home page which displays books of all authors which allows authors to see each other’s books. Author’s can edit/delete their own book, they can add a category to their book from existing list of categories, or they can add a new category for their book. There is also a standalone functionality to add / delete / update a category; however a category already assigned to a book cannot be edited or deleted.

