---
title: Contact
nav:
  order: 6
  tooltip: Contact person and channels
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{% capture content %}
{%
  include figure.html
  image="images/Mathematikon-IWR-9_0.jpeg"
  width="400px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

Barbara Werner<br>
Lab Manager<br>
Room 4.306<br>
Im Neuenheimer Feld 205<br>
69120 Heidelberg<br>

{%
  include button.html
  type="email"
  text="Email"
  link="hamprecht-lab-manager@iwr.uni-heidelberg.de"
%}
{%
  include button.html
  type="phone"
  text="+49 6221 54-14833"
  link="+49062215414833"
%}
{%
  include button.html
  type="address"
  text="Directions"
  tooltip="Our location on Google Maps for easy navigation"
  link="Interdisziplinäres+Zentrum+für+wissens.+Rechnen+IWR+der+Universität+Heidelberg/@49.4174921,8.6729896,17z/data=!3m1!4b1!4m6!3m5!1s0x4797c1320c285a31:0xf0a29f9fd73ab628!8m2!3d49.4174921!4d8.6755645!16s%2Fg%2F11b6d22h92?entry=ttu"
%}

{% include float.html clear=true %}