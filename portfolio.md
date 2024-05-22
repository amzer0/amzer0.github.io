---
layout: default
title: Portfolio
permalink: /portfolio/
---

<h2>Ballpoint Pen</h2>
<ul>
  {% for project in site.ballpoint_pen %}
  <li>
    <img src="{{ project.image }}" alt="{{ project.title }}>
      <h3>{{ project.title }}<h3>
      <p>{{ project.description}}<p>
  </li>
      {% endfor %}
</ul>

<h2>Traditional To Digital</h2>
<ul>
  {% for project in site.traditional_to_digital %}
  <li>
    <img src="{{ project.image }}" alt="{{ project.title }}>
      <h3>{{ project.title }}<h3>
      <p>{{ project.description}}<p>
  </li>
      {% endfor %}
</ul>

<h2>Commissions</h2>
<ul>
  {% for project in site.commissions %}
  <li>
    <img src="{{ project.image }}" alt="{{ project.title }}>
      <h3>{{ project.title }}<h3>
      <p>{{ project.description}}<p>
  </li>
      {% endfor %}
</ul>

<h2>Inktober</h2>
<ul>
  {% for project in site.inktober %}
  <li>
    <img src="{{ project.image }}" alt="{{ project.title }}>
      <h3>{{ project.title }}<h3>
      <p>{{ project.description}}<p>
  </li>
      {% endfor %}
</ul>
