---
title: "Ann Noble"
description: "You will free yourself from emotionally painful memories, switch off reoccurring unwanted thoughts and release yourselve from fear."
layout: index
categories:
tags:
---
{% for row in site.data.layout.index %}

{{ row }}
---
{% endfor %}




{% assign s = site.posts | size %}
{% assign col = s | minus: 1 | minus: 0 %}
{% assign post = site.posts[col] %}

  {{ post.excerpt }}


{% assign s = site.posts | size %}
{% assign col = s | minus: 1 | minus: 1 %}
{% assign post = site.posts[col] %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
