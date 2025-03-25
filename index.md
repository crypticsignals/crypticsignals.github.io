---
layout: default
title: "Home"
---

# Homepage test

## Recent Posts

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <strong><a href="{{ post.url }}">{{ post.title }}</a></strong> 
    <br>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>