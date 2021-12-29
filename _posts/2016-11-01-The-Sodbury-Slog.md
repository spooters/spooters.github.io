---
layout: post
title:  The Sodbury Slog 2016 
categories: [Running]
---

Well the Sodbury Slog lived up to expectation. Mud and a really nice course. Dave, Tony and I all completed the course despite little training. Its definitely an event I expect us to enter yearly along with the Horton Bull run. A well organised event will good amount of people competing.

As you can see. You get muddy!

### Race times.

Marcus 1:38:29.2 (349 / 1096)

Dave 1:46:03.9 (447 / 1096)

Tony 1:52:11.0 (513 / 1096)

<div class="post-categories">
  {% if post %}
    {% assign categories = post.categories %}
  {% else %}
    {% assign categories = page.categories %}
  {% endif %}
  {% for category in categories %}
  <a href="{{site.baseurl}}/categories/#{{category|slugize}}">{{category}}</a>
  {% unless forloop.last %}&nbsp;{% endunless %}
  {% endfor %}
</div>
