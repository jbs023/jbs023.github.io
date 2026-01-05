---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a complete publications list on my <a href="https://scholar.google.com/citations?user=qd4Y1-QAAAAJ&hl=en"> Google Scholar</a> profile.<br>
<sup>*</sup> Denotes equal authorship

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

