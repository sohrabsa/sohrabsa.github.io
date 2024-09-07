---
layout: page
permalink: /publications/
title: Publications
description: Here is a select number of my publications. For a complete list, please see my Google Scholar page <a href='https://scholar.google.com/citations?user=dyjNo_wAAAAJ'>here</a>.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">


<h1>Journal Articles</h1>

{% bibliography -f papers -q @*[type=first_author] %}

<h1>Contributed Articles</h1>

{% bibliography -f papers -q @*[type!=first_author] %}

</div>
