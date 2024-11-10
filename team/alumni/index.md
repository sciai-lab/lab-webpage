---
title: Alumni
---

# {% include icon.html icon="fa-solid fa-users" %}Alumni

This is an incomplete list of people who have worked with us in the past. A more comprehensive list will follow soon.


{% assign alumni = site["members"] | default: emptyarray | data_filter: "status: alumni" %}
{% assign alumni = alumni | concat: site.data.alumni-list %}
{% assign alumni = alumni | sort: "name" %}

Name | Role
---- | ----
{% for member in alumni -%}
    {% assign role = site.data.types[member.role].description -%}
    {% if member.url -%}
        [{{member.name}}]({{member.url}}) | {{role}}
    {% else -%}
        {{member.name}} | {{role}}
    {% endif -%}
{% endfor -%}

