---
layout: page
title: Projects
permalink: /projects/
---

Selected projects representing production-facing work in research data platforms, cohort analytics, and clinical study operations.

{% assign sorted_projects = site.projects | sort: "order" %}
{% for project in sorted_projects %}
### [{{ project.title }}]({{ project.url }})

{{ project.summary }}

**Tools:** {{ project.tools | join: ", " }}

---
{% endfor %}
