---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2>Preprints</h2>

{% bibliography -f {{ site.scholar.bibliography_reports }} %}

</div>

<h2>Publications</h2>

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
