---
pagination:
    data: apps
    size: 1
    alias: app
    resolve: values
permalink: "app/{{ app.name | slug }}/"
layout: index
app:
    name: Index Page
---
<h1>{{ app.name }}</h1>
