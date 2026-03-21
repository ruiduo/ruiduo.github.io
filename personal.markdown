---
layout: page
title: Personal
permalink: /personal/
---

Essays and Letters.
{% for post in site.categories.peculiarities %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}