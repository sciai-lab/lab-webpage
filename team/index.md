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
  image="images/team.jpg"
  caption="The SciAI lab in the Vosges in 2025"
  width="50%"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, status: ^(?!alumni$)" %}
{% include list.html data="members" component="portrait" filters="role: visiting-prof, status: ^(?!alumni$)" %}
{% include list.html data="members" component="portrait" filters="role: labmanager, status: ^(?!alumni$)" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|visiting-prof$|labmanager$), status: ^(?!alumni$)" %}

{% comment %}

### Members who don't have a member page yet
{:.center}

| Name  | Role  |
| :---- | :---- |
| Lennart Bürger | MSc Student |

{% endcomment %}

## Alumni

{%
  include button.html
  link="team/alumni"
  text="Our Alumni"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
