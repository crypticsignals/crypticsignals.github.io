---
layout: page
title: "All Blog Posts"
---

<ul>
{% for post in site.posts %}
  <li>
    <strong><a href="{{ post.url }}">{{ post.title }}</a></strong> 
    <br>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul> 