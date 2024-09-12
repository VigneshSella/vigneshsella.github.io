---
layout: page
title: "Projects"
permalink: /projects/
---

{% for post in site.categories.projects %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %Y" }}
{% endfor %}
