---
layout: archive
title: "Student Research Competition"
permalink: /src/
author_profile: true
---

{% include base_path %}

{% for post in site.srcompetitions reversed %}
  {% include archive-single.html %}
{% endfor %}

