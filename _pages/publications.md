---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Li, C., & Gao H., (2023a). Seismic evidence for metamorphic densification of the lower continental crust in eastern North America. Journal of Geophysical Research: Solid Earth.128(6). doi:10.1029/2023JB02660212.[Download paper here](http://academicpages.github.io/files/Li_etal_2023_eNA.pdf)
