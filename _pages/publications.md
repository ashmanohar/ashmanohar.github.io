---
layout: page
permalink: /publications/
title: Publications
nav: true
---

<div class="publications">
  <section>
  <h2>Peer-reviewed publications </h2>
  {% bibliography -f papers -q @article %}
  </section>
  <section>
  <h2>Conference proceedings</h2>
  {% bibliography -f papers -q @inproceedings %}
  </section>
  <!-- <section>
  <h2>In preparation</h2>
  {% bibliography -f papers -q @unpublished %}
  </section> -->
</div>
