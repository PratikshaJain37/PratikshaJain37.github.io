---
title: "Django Notes App"
# last_modified_at: 2016-03-09T16:20:02-05:00
tags:
  - django
  - notes
  - python
  - ckeditor
  - pythonanywhere
imagepath: "/assets/images/django-notes.jpg"
description: 'A simple, clean Notes WebApp'
---
<!--image-->
<img src="{{ page.imagepath | relative_url }}" alt="" height="400" width="400">

<!--background-->
The notes app in my phone is full of little nuggets of  gold: long forgotten phone numbers, shopping lists dictated in the car, passwords of sites that I would never use. 

It seems so redundant to not have one for the web; a place to store bookmarks and pictures and paragraphs and quotes, akin to pressing dried flowers between the pages of books.

### Aim: ###
To create a Notes App with Django, and deploy it.

### Progress: ###
<ul> 
<li> The database is set up from the admin side </li>
<li> Basic views have been created </li>
<li> A rich text editor (CKEditor) has been added. </li>
<li> Successfully deployed on Pythonanywhere </li>

</ul>

### Future Plans: ###
<ul>
<li> User Management </li>
<li> Password Protected notes </li>
<li> Option to save notes offline (export them) </li>
<li> Add tags/categories to classify them, and the associated views </li>
</ul>

### Technology Used: ###
<ul> 
<li> Django </li>
<li> Python </li>
<li> Basic Html/CSS </li>
<li> CKEditor </li>
</ul>

### Deployment: ###
The app has been successfully deployed <a href='http://pratikshajain37.pythonanywhere.com/'>here.</a>

Find the repository here: 
<a href="https://github.com/PratikshaJain37/django-notes">
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/github.png" height='40' width='40' alt="">
</a> 
