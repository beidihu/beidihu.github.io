---
layout: page
permalink: /publications/
title: research
description: Much of my research examines the psychology underlying everyday consumer decisions. Each paper below is accompanied by a short blurb that highlights the core intuition behind the research. To read the full academic abstract, click on "FULL ABSTRACT". If you are interested in a paper and can't access a copy, feel free to reach out. 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<h3> Working Papers </h3>

<div class="publications">
  {% bibliography --group_by none --query @*[work=true]* %}
</div>


<h3 style="margin-top: 3rem"> Peer-reviewed Journal Publications </h3>

<div class="publications">

{% bibliography --query @*[work=false]* %}

</div>
