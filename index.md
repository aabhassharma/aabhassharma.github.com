---
layout: page
title: Hello World!
tagline: Welcome to Aabhas's Page!
---
{% include JB/setup %}

Welcome to Aabhas Sharma's Github page! 
This site has been made possible thanks to the awesome folks behind <a href="http://jekyllbootstrap.com/">Jekyl</a>!

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

