---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please kindly refer to my articles on [my google scholar](https://scholar.google.com.sg/citations?user=2PxlmU0AAAAJ&hl=en). This page is only updated occasionaly.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
