---
title: Projects
icon: fas fa-code
order: 2
---

I’ll be adding write-ups here for class projects, senior design work, and small experiments as I learn.

{% assign project_posts = site.posts | where_exp: "p", "p.categories contains 'projects'" %}

{% if project_posts.size == 0 %}
Nothing posted here yet.
{% else %}
{% for post in project_posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% endif %}
