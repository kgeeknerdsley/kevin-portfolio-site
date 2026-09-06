---
title: "Projects"
permalink: /projects/
layout: archive
classes: wide
author_profile: true
---

Welcome to my collection of projects! I'm very proud of my role in each and every one.


Projects I've contributed to professionally is in the first carousel, followed by my university projects, then some interesting things I tinker with in my own time.

<h2 id="professional">Professional</h2>
<div class="grid__wrapper">
  {% assign professional = site.projects | where: "project_type", "professional" %}
  {% for post in professional %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>

<h2 id="college">University</h2>
<div class="grid__wrapper">
  {% assign college = site.projects | where: "project_type", "college" %}
  {% for post in college %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>

<h2 id="personal">Personal</h2>
<div class="grid__wrapper">
  {% assign personal = site.projects | where: "project_type", "personal" %}
  {% for post in personal %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>