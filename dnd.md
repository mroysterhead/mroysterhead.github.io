---
layout: dnd
title: "DND Notes"
permalink: /dnd/
---

{% for post in site.dnd %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}