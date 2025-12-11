---
layout: page
title: Home
permalink: /
---


Welcome to my Beautiful Jekyll-powered site! 👋


This is a short intro paragraph. Replace it with your content or drop in any HTML.


## Latest posts


{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
