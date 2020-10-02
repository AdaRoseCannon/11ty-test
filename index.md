---
layout: index
app:
    name: Web Apps
---

<h1>{{ app.name }}</h1>

<ul>
{%- for app in apps -%}
<li><a href="app/{{ app[1].name | slug }}/">{{ app[1].name }}</a></li>
{%- endfor -%}
</ul>
