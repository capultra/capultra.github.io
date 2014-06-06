---
layout: page
title: Capultra
tagline: Better through nutrition.
---
{% include JB/setup %}

{% for post in site.posts limit 5 %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{{ post.excerpt }}

---
{% endfor %}

