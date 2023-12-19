---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are physicists, mathematicians, computer scientists and engineers, united by the 💗 for science. One of us originally studied languages, and one is a chemist gone astray. 

{%
  include figure.html
  image="images/1811-group-outing.jpg"
  caption="2018 CE"
  link="team"
  width="30%"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: visiting-prof" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|visiting-prof$)" %}

### Short-term Members
{:.center}

| Name  | Role  |
| :---- | :---- |
| Finn Prem | BSc Student |

## Alumni

{%
  include button.html
  link="team/alumni"
  text="Our Alumni"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
