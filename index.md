---
layout: page
title: Posts
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2></li>
    <br>
    <span style="background-color:gray”>{{post.excerpt}}</span>

  {% endfor %}
</ul>
