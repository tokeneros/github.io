---
layout: default
title: Home
---

# Welcome to My Awesome Site

This is the home page.


{% for link in site.nav_links %}
{{ site.baseurl }}{{ link.url }}" - {{ link.title }}
{% endfor %}