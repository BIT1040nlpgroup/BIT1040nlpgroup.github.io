---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

## Conference

{% for post in site.conference reversed %}
{% include archive-single.html %}
{% endfor %}

## Journal

{% for post in site.journal reversed %}
{% include archive-single.html %}
{% endfor %}
