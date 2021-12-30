---
title: Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
author_profile: true

---

What I'm up to, in a productive sense...
{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
