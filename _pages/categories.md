---
title:  "Categories"
layout: archive
permalink: /categories/
author_profile: true
comments: true
---

{% for product in collection.products %}
  {{ product.title }}
{% endfor %}

