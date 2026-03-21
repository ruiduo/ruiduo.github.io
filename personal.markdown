---
layout: page
title: Personal
permalink: /personal/
---

Essays, Letters, and Lists.
{% for post in site.categories.personal %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}