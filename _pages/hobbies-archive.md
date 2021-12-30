---
title: Hobbies
layout: collection
permalink: /hobbies/
collection: hobbies
entries_layout: grid
classes: wide
author_profile: true

---

This is what I do in my free time!

{% include base_path %}

{% for post in site.hobbies %}
  {% include archive-single.html %}
{% endfor %}
