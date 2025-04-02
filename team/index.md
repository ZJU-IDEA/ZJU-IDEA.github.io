---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

**Lead PI:** Cheng Zhuo is a Qiushi Distinguished Professor and Tenured Full Professor at Zhejiang University.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.png" dark=true %}

Our team spans across the College of Integrated Circuits and the College of Information Science & Electronic Engineering with more than 50 members.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
