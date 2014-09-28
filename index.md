---
layout: default
title: Your New Jekyll Site
---

# Blog Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
