---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please find us at czhuo AT zju.edu.cn
<!-- 
{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %} -->

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}
浙江大学杭州国际科创中心（水博园区）
A03 511
杭州市萧山区平澜路2118号
{% endcapture %}

{% capture col3 %}
ZJU-Hangzhou Global Scientific and Technological Innovation Center
Building A03, Office 511, Water Expo Campus
2118 Pinglan Road
Xiaoshan, Hangzhou, China
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
