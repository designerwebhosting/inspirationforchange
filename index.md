---
title: "Ann Noble, Akashic therapist"
description: "You will free yourself from emotionally painful memories, switch off reoccurring unwanted thoughts and release yourselve from fear."
layout: index
categories:
  - ""
tags:
  - ""
---

{% for page in site.pages %}
  {% if page.title == 'home page for inspiration for change' %}{% include page.html %}{% endif %}
{% endfor %}

{% assign post = site.posts[1] %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
