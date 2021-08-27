---
title: Faculty
layout: page
---

{% for portfolio in site.portfolio %}
<h2>{{ portfolio.title }}</h2>
{{ portfolio.content }}

{% endfor %}

