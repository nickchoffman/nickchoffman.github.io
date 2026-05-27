---
layout: page
permalink: /publications/
title: Research
subtitle: "Research topics: Taxation, monetary policy, heterogeneous-agent macroeconomics, wealth and returns"
description: "Research topics: Taxation, monetary policy, heterogeneous-agent macroeconomics, wealth and returns"
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">

  <h2 class="category">Working Papers</h2>
  {% bibliography -f papers -q @*[category=working]* %}

  <h2 class="category">Works in Progress</h2>
  {% bibliography -f papers -q @*[category=progress]* %}

  <h2 class="category">Other Articles</h2>
  {% bibliography -f papers -q @*[category=other]* %}

</div>

{% bibliography -f papers %}

</div>
