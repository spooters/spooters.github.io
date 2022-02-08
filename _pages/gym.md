---
title: Gym
layout: page
permalink: /gym/
---

{% for post in site.categories.gym %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
