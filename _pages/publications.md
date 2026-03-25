---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For a full list of publications, see my [Google Scholar profile](https://scholar.google.com/citations?user=7TL5ZKsAAAAJ&hl=en).

{% include base_path %}

## Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
