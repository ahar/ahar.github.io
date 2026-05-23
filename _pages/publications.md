---
layout: page
permalink: /publications/
title: publications
description: Publications in robotics, autonomous systems, and sensor fusion.
years: [2024, 2023, 2019, 2018, 2015, 2014, 2013, 2012]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
