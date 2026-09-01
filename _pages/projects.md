---
layout: page
title: projects
permalink: /projects/
description: Verified data-science project work.
nav: true
nav_order: 4
display_categories: [data-science]
horizontal: false
---

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in sorted_projects %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
