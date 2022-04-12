---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page is not updated frequently. You can also find my articles on [my google scholar](https://scholar.google.com.sg/citations?user=2PxlmU0AAAAJ&hl=en)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
