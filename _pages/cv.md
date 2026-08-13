---
layout: archive
title: "CV"
permalink: /cv/
excerpt: "Curriculum vitae"
author_profile: true
---

Education
======

**Ph.D. in Physics (in progress)**, School of Physics, Beihang University, Beijing, China<br>
2024-present

**M.Sc. in Physics**, School of Physics, Harbin Institute of Technology, Harbin, China<br>
2020-2023

**B.Sc. in Physics**, School of Physics and Electronics, Shandong Normal University, Jinan, China<br>
2016-2020

Professional experience
======

**Chief Engineer**, The 36th Research Institute of China Electronics Technology Group Corporation (CETC), China<br>
2023-2024

Research interests
======

* Condensed-matter theory: quantum transport in topological insulators and topological superconductors; parity anomaly in condensed-matter systems
* DFT and artificial intelligence: machine learning and deep learning for materials screening, structure-property relationships, and inverse materials design
* Quantum computation and quantum optics

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
