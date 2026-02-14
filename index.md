---
layout: default
title: Jubilee Tan
permalink: /
---

# Jubilee Tan

<div class="home-hero">
  <img
    class="home-avatar"
    src="{{ '/assets/e379bc5f-b6cd-406e-8694-de4ddaf624a4.png' | relative_url }}"
    alt="Headshot of Jubilee Tan"
  />
  <div>
    <p><strong>Senior Application Developer | Research Informatics & Healthcare Data Engineering</strong></p>
    <div class="hero-cta-group" aria-label="Primary contact links">
      <a class="hero-cta" href="{{ '/assets/Jubilee_Tan_CV.pdf' | relative_url }}">Download CV (PDF)</a>
      <a class="hero-cta" href="https://www.linkedin.com/in/jubilee-tan-17b642109/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a class="hero-cta" href="https://github.com/jubilee2" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a class="hero-cta" href="mailto:jubilee2@gmail.com">Email</a>
    </div>
    <p>I build reliable data systems for clinical and biomedical research, with experience across large-scale cohort analytics, automated reporting, and REDCap-based study operations.</p>
  </div>
</div>

## Highlights

- 13+ years of professional software and data platform experience
- Senior Application Developer at Vanderbilt University Medical Center (Center for Quantitative Sciences)
- Contributor to NIH All of Us Research Program analytics and QC workflows
- Built and scaled automated reporting infrastructure supporting 200+ reports per week
- Delivered REDCap external support tooling for consent, reminders, randomization, data sync, and operational monitoring

## Featured Projects

{% assign featured_projects = site.projects | sort: "order" | slice: 0, 3 %}
{% for project in featured_projects %}
{{ forloop.index }}. [{{ project.title }}]({{ project.url | relative_url }}) — {{ project.summary }}
{% endfor %}

## Quick Links

- [About]({{ '/about/' | relative_url }})
- [Projects]({{ '/projects/' | relative_url }})
- [CV]({{ '/cv/' | relative_url }})
- [Contact]({{ '/contact/' | relative_url }})
