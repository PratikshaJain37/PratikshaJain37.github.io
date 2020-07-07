---
title: "Django Calculator"
# last_modified_at: 2016-03-09T16:20:02-05:00
tags:
  - django
  - python
  - calculator
  - sql
imagepath: "/assets/images/django-calc.jpg"
description: 'A basic calculator'
---
<!--image-->
<img src="{{ page.imagepath | relative_url }}" alt="" height="400" width="400">

<!--background-->
This is one of those apps that every 'Beginner Projects for Django' blogs suggest, as it helps in understanding how models, views, forms and html pages work together.  

I ran into a lot of errors while making it, and it really did help me understand how these core basics all work toegther. It also taught me how to Google more efficiently - there was terminology that I hadn't encountered before, and I had to figure out what exactly I wanted. 

### Aim: ###

To create a basic calculator app which given an input of 1 or 2 numbers, outputs the specified operation, and also displays the previous calculations

### Progress: ###
<ul> 
<li> The calculator performs the operations coded for successfully </li>
<li> It displays the results on a separate page, which also shows the last 5 successful operations. </li>
<li> Validation: It checks for valid numbers, and handles the errors accordingly. (An example of this would be when 2 numbers are provided for the Factorial option - An appropriate message should be shown) </li>

</ul>


### Future Plans: ###
<ul>
<li> Extend for multiple operations </li>
<li> Provide an option for the number of previous results to be displayed.</li>

</ul>

### Technology Used: ###
<ul> 
<li> Django Framework </li>
<li> Python </li>
</ul>

### Deployment: ###

Find the repository here: 
<a href="https://github.com/PratikshaJain37/django-basic-calculator">
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/github.png" height='40' width='40' alt="">
</a> 