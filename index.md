---
layout: default
title: Home
permalink: /
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
