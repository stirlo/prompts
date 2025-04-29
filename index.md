---
layout: home
title: Kagi Assistant Prompts
---

# Kagi Assistant Prompts Collection

A curated collection of useful prompts for Kagi Assistant and other LLMs.

## Latest Prompts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

[View All Prompts](/prompts) | [GitHub Repository](https://github.com/stirlo/prompts)
