---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

<ul>{% for post in site.experiences reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
