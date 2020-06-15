---
title: "Cypher-Decypher"
# last_modified_at: 2016-03-09T16:20:02-05:00
tags:
  - encryption
  - decryption
  - python
  - flask
imagepath: "{{ site.url }}{{ site.baseurl }}/assets/images/cypher.jpg"
---
<!--image-->
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/cypher.jpg" alt="">

<!--background-->
Ever since I was a little kid, I've always been enthralled by puzzles; be it the Sudokus featured daily in newspapers, or the multitude of brain teaser apps that came and went on my phone.

My favourite puzzle, however, will always be decoding little cyphers. I love the idea of sending encrypted messages, and decoding them.

<h3> Aim: </h3>
The project aims to both encrypt and decrypt messages, by using a variety of methods.

<h3> Progress: </h3>
The cyphers implemented include:
<ul> 
<li> Additive Cypher </li>
<li> Multiplicative Cypher </li>
<li> Hill Digraph Cypher </li>
</ul>

<h3> Future Plans: </h3>
<ul>
<li> Add more mathematically complex cyphers </li>
<li> Implement fuzzy matching to find keywords </li>
<li> Use concepts of relative frequency to match more efficiently to answers </li>
<li> Improve design of page </li>
<li> Add functionality for users, integrate with SQL to store their used keys - similar to a password keeper. </li>
</ul>

<h3> Technology Used: </h3>
<ul>
<li> Python for the functions which encode/decode the text </li>
<li> Flask Framework </li>
</ul>


<h3> Deployment: </h3>
It has been successfully deployed on <a href='https://cypher-decypher.herokuapp.com/'>Heroku.</a>

Find the repository here 
<a href="https://github.com/PratikshaJain37/cypher-decypher">
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/github.png" height='40' width='40' alt="">
</a> 