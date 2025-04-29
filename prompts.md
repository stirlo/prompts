---
layout: page
title: All Prompts
permalink: /prompts/
---

# All Kagi Assistant Prompts

Browse our complete collection of prompts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
