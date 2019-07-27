---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=dqhN0pkAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
