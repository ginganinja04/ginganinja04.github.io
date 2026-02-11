---
layout: page
title: Projects
icon: fas fa-code
order: 2
permalink:/projects/
---

{% assign project_posts = site.categories.Projects | sort: "date" | reverse %}

{% for post in project_posts %}
  {% include post-preview.html post=post %}
{% endfor %}

