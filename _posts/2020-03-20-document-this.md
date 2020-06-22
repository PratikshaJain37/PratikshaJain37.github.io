---
title: "Document-This"
# last_modified_at: 2016-03-09T16:20:02-05:00
tags:
  - documentation
  - hacks
imagepath: "/assets/images/document-this.jpg"
description: 'Giving a template for documentation'
---
<!--image-->
<img src="{{ page.imagepath }}" alt="">

<!--background-->
One problem that I encountered (as all new coders do), is documenting my work. Generally, I would write a rough pseudocode on paper, and implement it. I would forget to actually document it, and assumed that I would remember what I did for eternity.

Of course, we all know what happened.

In this context, a quote commonly attributed to Bill Gates comes to my mind:
"I will always choose a lazy person to do a difficult job because a lazy person will find an easy way to do it."

I ended up writing a python script to help me write the documentation for any code.

(Of course, this should not be used as formal documentation, but rather a template to summarize what you all did - It's much easier editing than it is to write something from scratch)

### Aim: ###
It is an ambitious script which gives a template of your python code for easier documentation.

The document aims to print all your comments and also tell you where (line number) you have used For/While loops, Try/Except/Else statement blocks, If/Elif/Else statement blocks, where you have called which function etc.

### Progress: ###
<ul> 
<li> Detected comments and unassigned multiline strings (used as multiline comments) </li>
<li> Detected For/While Loops </li>
<li> Detected If/Elif/Else Blocks</li>
<li> Detected Try/Except/Else Blocks </li>
<li> Detected defining a function </li>
<li> Detecting calling a self-defined function </li>
</ul>

### Future Plans: ###
<ul>
<li> Work on the bugs identified until now </li>

</ul>

### Technology Used: ###
<ul> 
<li> Basic Python </li>
</ul>


Find the repository here: 
<a href="https://github.com/PratikshaJain37/document-this">
<img src="{{ site.url }}/assets/images/github.png" height='40' width='40' alt="">
</a> 