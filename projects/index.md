---
title: Projects
nav:
  order: 1
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% capture text %}

- Compute-in-Memory systems design.
- Approximate digital circuits design.
-  Boolean satisfiability problem solver design.

{% endcapture %}

{%
  include feature.html
  image="images/projects/ASIC.jpg"
  title="Application Specific Integrated Circuit Design"
  style="bare"
  text=text
%}

Our open-sourced projects.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
