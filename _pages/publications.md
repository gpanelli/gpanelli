---
layout: archive
title: "Research"
<!-- permalink: /publications/ -->
permalink: /research/
author_profile: true
---
My current research includes XXX. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
  <br>
{% endfor %}
