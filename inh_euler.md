---
layout: default
title: Project Euler
permalink: /euler/
---

{: style="text-align:center"}
## **![euler](/assets/pe.ico){:style="width: 50px;"} My progress on [Project Euler](https://projecteuler.net/) problems.**

Click on a post to see my solution. Answer output is hidden behind a spoiler.  
Solutions to problems beyond 100 will not be posted; this is partially to honor site guidelines, but mostly because I don't know any of them (yet!). *[My profile](https://projecteuler.net/progress=AthenH)*

A few of these may be missing code, please bear with me as I try to scrounge everything together.

<ul>
  <hr>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      <hr>
    </li>
  {% endfor %}
</ul>