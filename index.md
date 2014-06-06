---
layout: page
title: Capultra
tagline: Better through nutrition.
---
{% include JB/setup %}

{% for post in site.posts offset: 0 limit: 5 %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
{{ post.excerpt }}

---
{% endfor %}

