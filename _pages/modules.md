---
layout: archive
title: "In-class Modules"
permalink: /modules/
author_profile: true
---

{% include base_path %}

{% for post in site.modules reversed %}
  {% include archive-single.html %}
{% endfor %}