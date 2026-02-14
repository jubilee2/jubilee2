---
layout: page
title: Projects
permalink: /projects/
---

Below are selected projects across healthcare data engineering, research informatics, and scientific modeling.

{% assign sorted_projects = site.projects | sort: "order" %}
{% for project in sorted_projects %}
### [{{ project.title }}]({{ project.url }})

{{ project.summary }}

**Tools:** {{ project.tools | join: ", " }}

---
{% endfor %}
