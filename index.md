---
layout: home
title: "Home"
---

# Homepage test

## Recent Posts

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Title</th>
    </tr>
  </thead>
  <tbody>
    {% for post in site.posts limit:5 %}
    <tr>
      <td>{{ post.date | date: "%Y-%m-%d" }}</td>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>
