---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

## 会议

{% for post in site.publications_conference reversed %}
{% include archive-single.html %}
{% endfor %}

## 期刊

{% for post in site.publications_journal reversed %}
{% include archive-single.html %}
{% endfor %}
