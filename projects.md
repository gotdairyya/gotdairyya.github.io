---
layout: default
title: Projects
---
<h1>Projects</h1>

<ul>
  {% for post in site.posts %}
    <li>
     {{ post.image }}
      <p><a href="{{ post.url }}">{{ post.header }}</a></p>
    </li>
  {% endfor %}
</ul>

<div class="row">
 {% for post in site.posts %}
    <div class="col-6">
    <a href="{{ post.url }}">
      <img src="./assets/projects/{{ post.image }}.png" alt="{{ post.header }}" class="img-thumbnail">
      <h3>{{ post.header }}</h3>
      </a>
    </div>
    {% endfor %}
     </div>