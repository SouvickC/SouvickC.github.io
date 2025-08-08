---
layout: home
author_profile: true
---

{% include base_path %}

## Projects
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

## Recent News
{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}

