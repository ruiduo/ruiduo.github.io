---
layout: page
title: Peculiarities
permalink: /peculiarities/
---

{% for post in site.categories.peculiarities %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}