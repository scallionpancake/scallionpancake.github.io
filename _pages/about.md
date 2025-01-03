---
layout: about
title: about
permalink: /
subtitle: material scientist at <a href='https://www.rapidliquidprint.co'>Rapid Liquid Print</a> | colloidal physics and rheology

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p><a href="mailto:kuei.steve@gmail.com"><i class="fa fa-envelope"></i> kuei.steve@gmail.com</p>
    <p><a href="https://scholar.google.com/citations?user=GRy8TgkAAAAJ&hl=en"><i class="fa fa-book"></i> google scholar</p>
    <p><a href="https://www.linkedin.com/in/stevekuei/"><i class="fab fa-linkedin"></i> linkedin</p>

news: false # includes a list of news items
social: false # includes social icons at the bottom of the page

display_categories: [academic, avocation]
---
Hello! this is under massive reconstruction right now.

My name is Steve Kuei; I'm a New Jersey native, and a researcher, a dancer, and an amateur cook - ostensibly, in that order. I am a material scientist in Boston specializing in complex fluid rheology, where I currently work on the fluid properties that allow for fluid-in-fluid 3D printing (or embedded printing) to operate at high speeds and great print fidelity.

I began my research career as an undergraduate at Princeton University, where I studied fiber knotting in fluid flow for my senior thesis with Professor Howard A. Stone. I then moved south, working on colloidal single fiber dynamics with Professor Sibani Lisa Biswal at Rice University. More recently, I was a postdoctoral fellow at the Gaithersburg campus of NIST, working with Dr. Steven D. Hudson on rodlike-fluid rheology and microstructure. 

I live by the phrase, "什麽略懂一些，生活就彩虹一些"; loosely translated, "if you learn a little bit of everything, your life will be that much more colorful."
As such, you'll find everything here from my academic endeavors to unresolved vectors of thought and miscellaneous pursuits.

Thank you for visiting, and I hope at least one of the pages here piques your interest! Feel free to contact me at <a href="mailto:kuei.steve@gmail.com">kuei.steve@gmail.com</a>
or to come find me in Boston :)

<!-- trying to add projects list to main page? 2024_0214-->

<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>