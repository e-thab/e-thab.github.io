---
layout: default
title: Project Euler
permalink: /euler/
---
# My progress on [Project Euler](https://projecteuler.net/) problems.  
### Click on a post to see my solution. Answer output is hidden behind a spoiler.  
### Solutions to problems beyond 100 will not be posted; this is partially to honor site guidelines, but mostly because I don't know any of them. *[My profile](https://projecteuler.net/progress=AthenH)*

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>