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

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  {{ post.content}}
{% endfor %}

{% include facebook.html %}
