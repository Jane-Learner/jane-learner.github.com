---
layout: page
title: Posts
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li> 
         <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
         <bl><span>{{ post.date | date_to_string }}</span><bl> </br></br>
    </li>
         <div>{{post.excerpt}}</div> 
  {% endfor %}
</ul>
