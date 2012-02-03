---
layout: page
title: blog of bakins
---
{% include JB/setup %}

Welcome to blog of bakins!

This is the blog of Brian Akins. Don't expect to learn anything.

Disclaimer: All views and opinions on this site belong to me and  do not necessarily represent those of the author's employer or any other entity. 
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



