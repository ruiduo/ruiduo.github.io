---
layout: page
title: Peculiarities
permalink: /peculiarities/
---

For the pieces that don't fit anywhere else. Essays, letters, and lists. 

{% for post in site.categories.peculiarities %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}