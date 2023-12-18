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
  link="ChIJRS21CDDBl0cR_ji7hcsaU_I"
%}

{% include float.html clear=true %}