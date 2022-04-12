---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{if author.googlescholar}
  This page is not updated frequently. You can also find my articles on <u><a href="{{https://scholar.google.com.sg/citations?user=2PxlmU0AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{end if}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
