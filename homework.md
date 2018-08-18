---
title: Homework
layout: page
---

New assignments will be added to this page through the semester.
Follow the link for the description of the homework assignment and forum.

Homework assignments:

{% for item in site.assignments %}
- {{ item.due }}: [{{ item.title }}]({{ item.url | absolute_url }}){% endfor %}
