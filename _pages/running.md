---
title: Running
layout: page
permalink: /running/
---

{% for post in site.categories.Running %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


<h1>{{ page.title }}</h1>
<div class="tags">
    {% assign sortedCategories = page.categories | sort %}
    {% for category in sortedCategories %}
        <span class="tag">
            <a href="/category/{{ category }}">#{{ category }}</a>
        </span>
    {% endfor %}
</div>
