---
layout: page
title: Sustainable Life Fitness
permalink: /sustainable-life-fitness/
---

# The Indigenous Wellness Disparity in America

Indian Health Service, the Federal Health Program for American Indians and Alaska Natives, notes "The American Indian and Alaska Native people have long experienced lower health status when compared with other Americans." in the form of "Lower life expectancy and the disproportionate disease burden." - [ihs.gov/newsroom/factsheets/disparities/](https://www.ihs.gov/newsroom/factsheets/disparities/)

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
