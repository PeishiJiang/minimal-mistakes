---
layout: archive
permalink: /researches/
author_profile: true
redirect_from:
  - /researches
---


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
