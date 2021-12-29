---
title: Running
layout: page
permalink: /running/
---

{% for post in site.categories.running %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
