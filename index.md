---
title: "Ann Noble, Akashic therapist"
description: "You will free yourself from emotionally painful memories, switch off reoccurring unwanted thoughts and release yourselve from fear."
layout: index
categories:
  - ""
tags:
  - ""
---
{% assign s = site.posts | size %}
{% assign col = s | minus: 1 | minus: 3 %}
{% assign post0 = site.posts[col] %}

  {{ post0.excerpt }}

{% assign s = site.posts | size %}
{% assign col = s | minus: 1 | minus: 0 %}
{% assign post = site.posts[col] %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
