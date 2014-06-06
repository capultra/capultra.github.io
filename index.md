---
layout: page
title: Capultra
tagline: Better through nutrition.
---
{% include JB/setup %}

{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a>
---------------------------------------------
{{ post.date | date_to_string }}

---
{% endfor %}

