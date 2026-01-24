---
layout: page
permalink: /publications/
title: publications
description: To see a full list of my working papers, please see my CV.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->


<div class="publications">
  {% bibliography --group_by none --query @*[selected=true]* %}
</div>

<div class="publications">

{% bibliography %}

</div>
