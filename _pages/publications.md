---
layout: archive
title: "Publications"
permalink: /publications/
excerpt: "Publications by Yanmiao Han"
author_profile: true
---

My current publication record is also available on [Google Scholar](https://scholar.google.com/citations?user=6bR6AfIAAAAJ&hl=en) and [ORCID](https://orcid.org/0009-0008-9562-5287).

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
