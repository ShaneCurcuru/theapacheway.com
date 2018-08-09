---
layout: archive
title: "Various mottos about the Apache Way"
permalink: /mottos/
author_profile: false
---

{% include base_path %}

{% assign thiscol = site.collections | where: "label", "mottos" | first %}
<h3>{{ site.mottos.excerpt }}</h3>

{% for post in site.mottos %}
  {% include archive-single.html %}
{% endfor %}