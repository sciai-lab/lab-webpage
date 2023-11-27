---
title: Contact
nav:
  order: 5
  tooltip: Contact, Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{% capture content %}
{%
  include figure.html
  image="images/Mathematikon-IWR-9_0.jpeg"
  caption="© IWR / Heidelberg University"
  width="400px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

- Barbara Werner
- Lab Manager
- Room 4.306
- Im Neuenheimer Feld 205
- 69120 Heidelberg

{% include float.html clear=true %}



{%
  include button.html
  type="email"
  text="hamprecht-lab-manager@iwr.uni-heidelberg.de"
  link="hamprecht-lab-manager@iwr.uni-heidelberg.de"
%}
{%
  include button.html
  type="phone"
  text="(0622) 154-14833"
  link="+490622-154-14833"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/Riy78Hikizpj2v5p6"
%}
