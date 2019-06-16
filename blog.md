---
layout: page
title: Blog
permalink: /blog
---
<section id="main" class="wrapper style1">
<h2>Udacity</h2>
<p><a href="https://medium.com/@UdacityINDIA/everything-cool-from-tensorflow-developer-summit-2018-7e22da4913de">TF developer summit 2018</a></p>

<p><a href="https://medium.com/@UdacityINDIA/popular-concepts-of-deep-learning-3f3f57b1574b">Popular concepts of Deep learning</a></p>

<p><a href="https://medium.com/@UdacityINDIA/why-use-python-for-machine-learning-e4b0b4457a77">Python for Machine Learning</a></p>


  {% for e in site.external_feed %}
    <h2>{{ e.title }}</h2>
    <p><a href="{{ e.link }}">Read More</a></p>
  {% endfor %}


