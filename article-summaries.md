---
title: "Article Summaries"
permalink: /article-summaries/
author_profile: true
---

# Article Summaries

In this section, I share concise summaries and critical appraisals of scientific papers related to medical physics, radiation physics, imaging, dosimetry, radiotherapy, and clinical research.

Each article summary may include:

- Citation
- Research question
- Study design
- Methods
- Main findings
- Strengths
- Limitations
- Clinical or scientific relevance
- My takeaway

## Posts

{% for post in site.categories.Article-Summaries %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
