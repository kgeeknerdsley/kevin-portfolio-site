---
title: "Projects"
permalink: /projects/
layout: archive
classes: wide
author_profile: true
---

Welcome to my collection of projects! I'm very proud of my role in each and every one. Certainly not an exhaustive list, but definitely some of the most exciting.


Projects are sorted by my Professional experience, University projects, and some Personal projects I tinker with in my spare time.

<h2 id="professional">Professional</h2>
<div class="grid__wrapper">
  {% assign professional = site.projects | where: "project_type", "professional" | sort: "order", "last" %}
  {% for post in professional %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>

<h2 id="college">University</h2>
<div class="grid__wrapper">
  {% assign college = site.projects | where: "project_type", "college" | sort: "order", "last" %}
  {% for post in college %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>

<h2 id="personal">Personal</h2>
<div class="grid__wrapper">
  {% assign personal = site.projects | where: "project_type", "personal" | sort: "order", "last" %}
  {% for post in personal %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div style="clear: both;"></div>