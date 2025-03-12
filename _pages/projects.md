---
layout: page
title: Working papers & Work in progress
permalink: /projects/
description:
nav: false
nav_order: 2
horizontal: false
---

<!-- pages/projects.md -->
<h4 class="category">Working papers</h4>
<div class="publications">
  {% bibliography -f papers --template bibsimple -q @*[papercat =4]* %}
</div>
<br>
<h4 class="category">Work in progress</h4>
<div class="publications">
  {% bibliography -f papers --template bibsimple -q @*[papercat =6]* %}
</div>