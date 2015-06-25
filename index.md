---
layout: page
title: Bienvenidos
tagline: blabloblablo
---
{% include JB/setup %}

Esta es una prueba blablo

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

##Este es un título h2

[este es un enlace](http://#)!

Más blablo

