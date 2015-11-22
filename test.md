---
title: testimonials
description: See what others have to say about how Ann Noble is making a differance in their lives.
layout: page
categories: blog
tags: menu
---
#test

{% for page in site.pages %}
{%  if page.path == '_pages/magenta.md' %}
{% include panel.html  %}
{% endif %}
{% endfor %}


{% include accordion.html accordPage="heather.md" %}
{% include accordion.html accordPage="magenta.md" %}
{% include accordion.html accordPage="micheala.md" %}
{: .panel-group #accordion}
