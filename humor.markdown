---
layout: page
title: Humor
permalink: /humor/
---

{% for post in site.categories.humor %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}