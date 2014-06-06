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

<a href="{{ BASE_PATH }}{{ site.JB.archive_path }}">More posts...</a>
