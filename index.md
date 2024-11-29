---
layout: default
title: Home
---

# Welcome to My Personal Website

Hello! I'm Gasorekibo. This is my personal website where I share my thoughts, projects, and experiences.

## Recent Posts
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}