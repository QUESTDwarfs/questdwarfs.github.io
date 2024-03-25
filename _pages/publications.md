---
layout: page
permalink: /publications/
title: Publications
years: [2024]
nav: true
nav_order: 5
social: false
---

Below is a list of primary publications from the QUEST Dwarfs team.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
