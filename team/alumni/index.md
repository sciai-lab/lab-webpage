---
title: Alumni
---

# {% include icon.html icon="fa-solid fa-users" %}Alumni

This is an incomplete list of people who have worked with us in the past. A more comprehensive list will follow soon.

Name | Role
---- | ----
{% assign data = site["members"] | default: emptyarray | data_filter: "status: alumni" %}{% for member in data %}{% assign role = site.data.types[member.role].description %} [{{member.name}}]({{member.url}}) | {{role}}
{% endfor %} Fahimeh Moafian | Postdoctoral Researcher

