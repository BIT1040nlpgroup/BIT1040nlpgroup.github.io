---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

## 会议

{% for post in site.conf reversed %}
{% include archive-single.html %}
{% endfor %}

## 期刊

{% for post in site.journal reversed %}
{% include archive-single.html %}
{% endfor %}
