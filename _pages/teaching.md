---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

<br><br>

# Instructional Experience

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

<br><br>

# Instructional Coursework and Certification

{% for post in site.teaching-certification reversed %}
  {% include archive-single.html %}
{% endfor %}
