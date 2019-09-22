# Where do you wanna go? 

<div>
  <nav>
    {% for project in site.projects %}
    {% if project.category == "project" %}
      <li><a href="{{ project.url }}">{{ project.title }}</a></li>
    {% endif %}
  {% endfor %}
  </nav>
</div>
