---
layout: page
title: Capultra
tagline: Better through nutrition.
---
{% include JB/setup %}

{% for post in site.posts %}
{{ post.title }}
{{ post.excerpt }} 
{% endfor %}

