---
title: Running
layout: page
permalink: /running/
---

{% for post in site.categories[page.category] %}
    <a href="{{ post.url | absolute_url }}">
      {{ post.title }}
    </a>
{% endfor %}
