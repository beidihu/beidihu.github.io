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

<h3> Working Papers </h3>

<div class="publications">
  {% bibliography --group_by none --query @*[work=true]* %}
</div>


<h3> Peer-reviewed Journal Publications </h3>

<div class="publications">

{% bibliography --query @*[work=false]* %}

</div>
