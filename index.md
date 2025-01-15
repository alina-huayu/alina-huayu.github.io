---
layout: page
title: Blog
permalink: /index.html
---


{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <br>
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}


