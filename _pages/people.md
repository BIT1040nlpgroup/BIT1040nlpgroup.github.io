---
layout: archive
title: "科研团队"
permalink: /people/
author_profile: true
---
{% include base_path %}

### 教师

---

### 在读学生

{% for post in site.people reversed %}

{% if post.collection == "people" %}

{% include archive-single.html %}

{% endif %}
{% endfor %}

---

### 已毕业学生

{% for post in site.grad%}
{% include archive-single.html %}
{% endfor %}
