---
layout: archive
title: "people"
permalink: /people/
author_profile: true
---
{% include base_path %}

{% for post in site.people reversed %}
{% include archive-single.html %}
{% endfor %}
