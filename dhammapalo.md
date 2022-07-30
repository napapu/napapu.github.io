---
layout: page
title: Dhammapalo
permalink: /dhammapalo/
---
This is a list of all the posts journaling my brief time between January and March 2020 as a Buddhist monk. They are in ascending chronological order.

When a layperson is ordained as a monk, they are given a [Pali](https://en.wikipedia.org/wiki/Pali){:target="_blank"} name. I was given the name Dhammapalo, which means the guardian of Dhamma. These names are rarely used though between Thai monks as they still refer to each other using their Thai nicknames. However, monks of the [Western Sangha](https://www.abhayagiri.org/about/western-sangha){:target="_blank"} refer to each other via their given Pali name.

<h3>Reflections</h3>

<ul>
  {% for post in site.categories.reflection reversed %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<h3>All posts</h3>

<ul>
  {% for post in site.categories.dhammapalo reversed %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>