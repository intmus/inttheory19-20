---
title: Homework
layout: page
---

New assignments will be added to this page through the semester.
Follow the link for the description of the homework assignment and forum.

Homework assignments:

<div id="fallSemester" class="assignments">
<h2>Fall Semester Homework</h2>
{% assign fall = site.assignments | where_exp: "item","item.relative_path contains 'Fall-semester'" %}
<ul id="fallSemesterList">
{% for item in fall %}
<li>{{ item.due }}: <a href="{{ item.url | absolute_url }}">{{ item.title }}</a> (<a href="{{ item.url | absolute_url }}#disqus_thread">0 Comments</a>)</li>{% endfor %}
</ul>
</div>

<div id="springSemester" class="assignments">
<h2>Spring Semester Homework</h2>
{% assign spring = site.assignments | where_exp: "item","item.relative_path contains 'Spring-semester'" %}
<ul id="springSemesterList">
{% for item in spring %}
<li>{{ item.due }}: <a href="{{ item.url | absolute_url }}">{{ item.title }}</a> (<a href="{{ item.url | absolute_url }}#disqus_thread">0 Comments</a>)</li>{% endfor %}
</ul>
</div>

<script>
/* toggle */
function assignmentsToggle(element) {
    document.getElementById(element).style.display = (document.getElementById(element).style.display === "block") ? "none" : "block";
}
/* open + close */
document.getElementById("fallSemester").onclick = function () { assignmentsToggle("fallSemesterList"); };
document.getElementById("springSemester").onclick = function () { assignmentsToggle("springSemesterList"); };
</script>