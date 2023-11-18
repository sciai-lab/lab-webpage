---
title: The Team :-) 
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a mixed team of physicists, mathematicians, computer scientists and engineers. One of us has studied languages, and one is a chemist gone astray. 



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
