---
layout: page
permalink: /publications/
title: Publications
nav: true
---

<div class="publications">
  <section>
  <h2>Journal papers</h2>
  {% bibliography -f papers -q @article %}
  </section>
  <h2>Conference proceedings</h2>
  {% bibliography -f papers -q @inproceedings %}
  <!-- <h2>In preparation</h2>
  {% bibliography -f papers -q @unpublished %} -->
</div>
