---
title: Summary
layout: page
permalink: /summary/
---

<h1>{{ page.title }}</h1>
<div class="tags">
    {% assign sortedCategories = page.categories | sort %}
    {% for category in sortedCategories %}
        <span class="tag">
            <a href="/category/{{ category }}">#{{ category }}</a>
        </span>
    {% endfor %}
</div>