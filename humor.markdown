---
layout: page
title: Humor
permalink: /humor/
---

I took a Writing Humor class Spring 2026 where I have to write a humorous essay about once a week. I'll try my hardest to continue the tradition of writing a humorous essay ~ 500 words once a week. They won't always be published as I won't always like them. Might upload some sketch scripts as well. Funny knickknacks and whatnot. 

{% for post in site.categories.humor %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

