---
layout: page
permalink: /publications/
title: Publications
description: Following are my research works and publications till date.
years: [2022]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
