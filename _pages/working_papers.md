---
layout: page
permalink: /working_papers/
title: Working Papers
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
  {% bibliography -f papers -q @*[category=working_paper]* %}
</div>
