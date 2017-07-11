---
title: "Ann Noble"
description: "You will free yourself from emotionally painful memories, switch off reoccurring unwanted thoughts and release yourselve from fear."
layout: index
categories:
tags:
---
{% for row in site.data.layouts.index %}

{% assign s = site.posts | size %}
{% assign x = row.row | size %}
{% assign columns = 12 | divided_by: x %}
{% for c in row.row %}
{% assign col = s | minus: 1 | minus: c.story %}
{% assign post = site.posts[col] %}
{% if c.title == true %}
{{ post.title }}
{% endif %}
{{ post.excerpt }}
{% endfor %}


{% endfor %}





