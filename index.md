---
layout: page
title: Hello There!
tagline: Zhenqiang.YING's personal blog
---
{% include JB/setup %}

## Home

﻿Welcome to my homepage! I am {{ site.author.name }}. My field of specialization is **Computer Vision** and I currently work at a startup. 

 * CV: [Consult my curriculum vitae]( {{ BASE_PATH }}/CV.html )
 * Contact: {{ site.author.email }}
 * GitHub: [baidut](https://github.com/baidut/)

I hope you enjoy this site. Thank you for your visit!
<!-- my LinkedIn public profile -->

<!-- About this blog, about the posts -->

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
