---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{if author.googlescholar}
  This page is not updated frequently. You can also find my articles on <u><a href="{{2PxlmU0AAAAJ&hl}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
