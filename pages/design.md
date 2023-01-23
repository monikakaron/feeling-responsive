---
layout: page
show_meta: false
title: Travel Options
subheadline: Different Tour Options You Can Make
header:
  image_fullwidth: Lofoten_2022.jpg
permalink: /design/
published: true
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
