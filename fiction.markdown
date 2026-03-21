---
layout: page
title: Fiction
permalink: /fiction/
---

Fiction I've written.
{% for post in site.categories.peculiarities %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}