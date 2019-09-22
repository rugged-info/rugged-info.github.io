---
title: home
---

# This is the front page of the website!

Where do you want to go? 

<nav>
  {% for project in site.projects %}
  {% if project.category == "project" %}
    <li><a href="{{ project.permalink }}">{{ project.title }}</a></li>
  {% endif %}
{% endfor %}
</nav>


{{ site.github.zip_url }}