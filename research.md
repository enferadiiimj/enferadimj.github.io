---
title: "Research"
permalink: /research/
author_profile: true
---

# Research

This page summarizes my research interests, academic projects, and future research directions.

## Research Interests

- Medical Physics
- Radiation Physics
- Dosimetry
- Radiotherapy Physics
- Medical Imaging
- Nuclear Medicine
- Radiation Protection
- Clinical Applications of Physics
- Quantitative Imaging
- Evidence-Based Medicine

## Current Projects

Coming soon.

## Future Directions

I am interested in developing a stronger understanding of how physics-based methods can improve diagnosis, treatment planning, radiation safety, and clinical decision-making.

## Research Notes

{% for post in site.categories.Research %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
