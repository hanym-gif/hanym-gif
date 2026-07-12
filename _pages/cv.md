---
layout: archive
title: "CV"
permalink: /cv/
excerpt: "Curriculum vitae"
author_profile: true
---

Education
======

**PhD in Physics**, School of Physics, Beihang University, Beijing, China  
2024-present

Research interests
======

* Condensed-matter theory and topological quantum transport
* First-principles materials modelling
* Interpretable machine learning for physical sciences
* Quantum computation, noise, and error correction

Publications
======

{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
1. **{{ post.title }}**  
   {{ post.authors }}  
   *{{ post.venue }}* ({{ post.date | date: "%Y" }}). [DOI]({{ post.paperurl }})
{% endfor %}

Profiles and contact
======

* [Google Scholar](https://scholar.google.com/citations?user=6bR6AfIAAAAJ&hl=en)
* [ORCID](https://orcid.org/0009-0008-9562-5287)
* [Web of Science ResearcherID](https://www.webofscience.com/wos/author/record/MTA-6093-2025)
* [GitHub](https://github.com/hanym-gif)
* [ymhan@buaa.edu.cn](mailto:ymhan@buaa.edu.cn)
