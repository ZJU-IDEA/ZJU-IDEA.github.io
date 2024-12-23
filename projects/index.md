---
title: Projects
nav:
  order: 1
  tooltip: Major research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% capture text %}

- Compute-in-Memory systems design.
- Approximate digital circuits design.
- Boolean satisfiability problem solver design.

{% endcapture %}

{%
  include feature.html
  image="images/projects/ASIC.jpg"
  title="Application Specific Integrated Circuit Design"
  style="bare"
  text=text
%}

{% capture text %}

- Co-Optimizations: Design space explorations.
- Micro-architecture optimizations.
- LLMs for design-manufacture co-optimization.

{% endcapture %}

{%
  include feature.html
  image="images/projects/fabgpt.jpg"
  title="Chip Design Optimizations"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

- Edge deployment of video perception applications.
- Deep learning inference acceleration.
- Distributed and federated learning frameworks.

{% endcapture %}

{%
  include feature.html
  image="images/projects/system.jpg"
  title="System Optimizations"
  style="bare"
  text=text
%}


{% capture text %}

- Power noise verification.
- Fast simulation for chiplet-based systems.
- Co-optimziation for time analysis.

{% endcapture %}

{%
  include feature.html
  image="images/projects/eda.jpg"
  title="EDA Tools"
  flip=true
  style="bare"
  text=text
%}


{% include section.html %}

## Open-Sourced Projects

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include list.html component="card" data="projects" filter="!group" style="small" %}
