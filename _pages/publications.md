---
layout: page
title: "Publications"
permalink: /publications/
---

## My Publications

{% for post in site.categories.publications %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %Y" }}
{% endfor %}
