---
layout: archive
title: "people"
permalink: /people/
author_profile: false
---
# 教师


---

# 在读学生

{% include base_path %}

{% for post in site.people reversed %}
{% include archive-single.html %}
{% endfor %}



---

# 已毕业学生

{% include base_path %}

{% for post in site.grad reversed %}
{% include archive-single.html %}
{% endfor %}
