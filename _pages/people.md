---
layout: archive
title: "科研团队"
permalink: /people/
author_profile: true
---
### 教师

---

### 在读学生

{% include base_path %}

{% for post in site.people reversed %}

{% if post.collection == "people" %}

{% include archive-single.html %}

{% endif %}
{% endfor %}

---

### 已毕业学生

{% include base_path %}

{% for post1 in site.people reversed %}

{% if post1.collection == "grad" %}
{% include archive-single.html %}

{% endif %}
{% endfor %}
