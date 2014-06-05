---
layout: page
title: Capultra
tagline: Better through nutrition.
---
{% include JB/setup %}

{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a>
---------------------------------------------
{{ post.excerpt }} 
<a href="{{ post.url }}">Read more...</a>

---
{% endfor %}

