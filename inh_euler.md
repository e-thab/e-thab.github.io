---
layout: default
title: Project Euler
permalink: /euler/
---

{: style="text-align:center"}
## **![euler](/assets/pe.ico){:style="width: 50px;"} My progress on [Project Euler](https://projecteuler.net/) problems.**

Click on a post to see my solution. Answer output is hidden behind a spoiler.  
Solutions to problems beyond 100 will not be posted; this is of course purely to honor site guidelines, not because I don't know any of them... of course. *[My profile](https://projecteuler.net/progress=AthenH)*

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