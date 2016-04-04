---
layout: rail
title:  "Programs"
date:   2016-3-30 11:18:36
prototype-title: Responsive Programs Page
prototyped-by: Josh
prototype-desc: Bringing the programs directory into responsive-land
---
<div class="program-wrapper">
  <ul class="news-programs">
    {% for program in site.data.programs %}
      <li class="program">
      <h1 class="title">{{ program.name }}</h1>
      <p>{{ program.description }}</p>
      </li>
    {% endfor %}
  <ul>
</div>
