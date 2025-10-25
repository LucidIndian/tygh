---
layout: page
title: Sustainable Life Fitness
permalink: /sustainable-life-fitness/
---

# Perspectives on the Indigenous Wellness Disparity in America

## Why are Indigenous and American Indians less healthy than non-Indigenous people?

Exploring today's health crises of Indigenous and American Indian tribes through the cultural lens of the [Brothertown Indian Nation](https://brothertownindians.org/).

<ul>
{% for post in site.posts %} 
{% if post.categories contains "Indigenous Wellness" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>

_These articles are intended for educational and cultural purposes only. Nothing on this site constitutes medical advice, diagnosis, or treatment. Always consult a licensed healthcare professional with questions or concerns about your health or medical conditions._
