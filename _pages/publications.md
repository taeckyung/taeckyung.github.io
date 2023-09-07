---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<br>

<h4>Conference & Workshop</h4>

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @*[conference=true]* %}

</div>

<br>

<h4>Poster & Demo</h4>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @*[conference=false] %}

</div>
