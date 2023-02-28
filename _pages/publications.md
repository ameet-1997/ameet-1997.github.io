---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2020, 2019, 2018]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<!-- Look at /_layouts/bib.html for button options -->
<!-- Colors for buttons are here: /Users/ameet/Stuff/Academics/Personal_Website/ameet-1997.github.io/_data/venues.yml -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
