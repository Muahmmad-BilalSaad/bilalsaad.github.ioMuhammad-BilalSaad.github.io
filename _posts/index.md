---
layout: home
title: Home
---

# Welcome to My Blog 🚀

Yahan meri latest posts hain:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
