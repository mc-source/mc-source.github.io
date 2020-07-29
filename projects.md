---
layout: default
title: Projects
---
### Latest Projects

<ul>
  {% for project in site.data.projects %}
    <li>
      <h4><a href="{{ project.url }}">{{ project.title }}</a></h4>
      {{ project.excerpt }}
    </li>
  {% endfor %}
</ul>

<!-- *   #### [{{ project.title }}]({{ project.url }})

    {{ project.excerpt }} -->