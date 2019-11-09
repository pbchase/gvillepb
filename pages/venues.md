---
layout: page
show_meta: false
title: "Places to play pickleball in Gainesville"
header:
   image_fullwidth: "paddles_at_jtc.jpg"
permalink: "/venues/"
---
<ul>
    {% for post in site.categories.venues %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>