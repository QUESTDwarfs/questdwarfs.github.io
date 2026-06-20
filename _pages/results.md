---
layout: page
title: Results
permalink: /research/
# description: A growing collection of your cool projects.
nav: true
nav_order: 3
display_categories: [Baryon Cycle, Circumgalactic Medium, Feedback] #[Physical Properties, CGM, Star Formation]
horizontal: false
social: false
---

Because of the breadth of galaxies in this sample and the multiwavelength coverage of both spectra and imaging, we are able to study the connection between the chemical and physical properties of these myriad galaxies in exceptional detail. You can explore our datasets here or see how to access them on our [Data](https://questdwarfs.github.io) page.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe src="/assets/html/quest_absorbers_lowres.html" frameborder='0' scrolling='no' height="445px" width="800pt"></iframe>
    </div>
</div>

*Open full resolution interactive [here](https://questdwarfs.github.io/assets/html/quest_absorbers.html) (recommended).*




We highlight here some of the major results from the QUEST Dwarfs project.


<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>


<hr style="height:1px; visibility:hidden;" />
