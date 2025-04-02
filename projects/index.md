---
title: Projects
nav:
  order: 1
  tooltip: Major research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% capture text %}

- 存内计算.
- 近似计算.

{% endcapture %}

{%
  include feature.html
  image="images/projects/ASIC.jpg"
  title="低功耗电路与系统"
  style="bare"
  text=text
%}

{% capture text %}

- 设计空间探索.
- 深度学习算子适配.
- 轻量化学习架构.

{% endcapture %}

{%
  include feature.html
  image="images/projects/fabgpt.jpg"
  title="人工智能赋能设计"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

- 视频增强与去噪。
- 高效能硬件加速器.
- 高可靠性设计.

{% endcapture %}

{%
  include feature.html
  image="images/projects/system.jpg"
  title="软硬件协同设计"
  style="bare"
  text=text
%}


{% capture text %}

- 高精度并行化仿真.
- 线性/非线性求解器.
- 电源信号完整性.

{% endcapture %}

{%
  include feature.html
  image="images/projects/eda.jpg"
  title="数值仿真与优化"
  flip=true
  style="bare"
  text=text
%}


{% include section.html %}

## Open-Sourced Projects

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include list.html component="card" data="projects" style="small" %}
