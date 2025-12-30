---
layout: default
title: Home
---


Welcome to **OOTD Rate Blog**.


We explore how **AI evaluates outfits**, breaks down celebrity looks, and helps you dress better using data-driven fashion insights.


---


### Latest Posts


{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}