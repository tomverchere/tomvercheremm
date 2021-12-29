---
title: Portfolio
layout: collection
permalink: /portfolio/
author_profile: true
collection: portfolio
entries_layout: grid
classes: wide
---

Sample document listing for the collection `_portfolio`.

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}