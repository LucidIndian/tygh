---
layout: page
title: Sustainable Life Fitness
permalink: /sustainable-life-fitness/
---

## Perspectives on Indigenous Wellness

### Why are Indigenous Americans less healthy than non-Indigenous?

Examining the modern health crises of Indigenous Americans through the lens of the culture of the Brothertown Indian Nation.

<ul>
{% for post in site.posts %} 
{% if post.categories contains "Indigenous Wellness" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>

_These articles are intended for educational and cultural purposes only. It does not constitute medical advice, diagnosis, or treatment. Always consult a licensed healthcare professional regarding any questions or concerns about your health or medical conditions._
