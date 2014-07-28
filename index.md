---
layout: page
title: Posts
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2></li>
    <div class=“index_content” >{{post.excerpt}}</div> 
</div>
  {% endfor %}
</ul>
