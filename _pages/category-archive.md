---
title: "Posts by Category"
layout: categories
permalink: /categories/
author_profile: true
---

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
