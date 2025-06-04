---
layout: default
title: "Home"
---

Good afternoon and welcome to my blog. Feel free to check the [Recent Posts](#recent-posts) header below for my most recent posts.

As I find more time, I will introduce more customization to the page.

# Recent Posts

<ul>
{% for post in site.posts limit:5 %}
  <li>
    <strong><a href="{{ post.url }}">{{ post.title }}</a></strong> 
    <br>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>

> Want to see more? Visit the list of every post I’ve written [here](./posts.html)