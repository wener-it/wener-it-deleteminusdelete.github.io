---
permalink: /portfolio/
layout: archive
title: "Portfolio"
author_profile: true
---

<div class="grid__wrapper">
  {% for post in site.portfolio %}
      {% include archive-single.html type="grid" %}
  {% endfor %}
</div>