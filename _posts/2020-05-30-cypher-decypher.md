---
title: "Cypher-Decypher"
tags:
  - encryption
  - decryption
  - python
  - flask
  - heroku
imagepath: "/assets/images/cypher-decypher.jpg"
description: 'Encoding and decoding data using different ciphertexts'
---
<!--image-->
<img src="{{ page.imagepath | relative_url }}" alt="" height="400" width="400">

<!--background-->
Ever since I was a little kid, I've always been enthralled by puzzles; be it the Sudokus featured daily in newspapers, or the multitude of brain teaser apps that came and went on my phone.

My favourite puzzle, however, will always be decoding little cyphers. I love the idea of sending encrypted messages, and decoding them. 

### Aim: ###
The project aims to both encrypt and decrypt messages, by using a variety of methods.

### Progress: ###
The cyphers implemented include:
<ul> 
<li> Additive Cypher </li>
<li> Multiplicative Cypher </li>
<li> Hill Digraph Cypher </li>
</ul>

### Features To Work On: ###
<ul>
<li> Add more mathematically complex cyphers </li>
<li> Implement fuzzy matching to find keywords </li>
<li> Use concepts of relative frequency to match more efficiently to answers </li>
<li> Improve design (css) of page </li>
<li> Add feature for user management - Similar to a password keeper </li>
</ul>

### Technology Used: ###
<ul>
<li> Python for the functions which encode/decode the text </li>
<li> Flask Framework </li>
</ul>


### Deployment: ###
The app has been successfully deployed <a href='https://cypher-decypher.herokuapp.com/'>here.</a>

Find the repository here: 
<a href="https://github.com/PratikshaJain37/cypher-decypher">
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/github.png" height='40' width='40' alt="">
</a> 