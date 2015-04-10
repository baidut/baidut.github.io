---
layout: page
title: Hello There!
tagline: Zhenqiang.YING's personal blog
---
{% include JB/setup %}

## Home

﻿Welcome to my homepage! I am {{ site.author.name }}. My field of specialization is **Computer Vision** and I currently work at a startup. 

 * You can consult my curriculum vitae [here]( {{ BASE_PATH }}/CurriculumVitae.html )
	 * PDF can be downloaded [here]()	 
	 * View my LinkedIn public profile [here](https://www.linkedin.com/pub/振强-应/b6/482/934)
 * Contact: {{ site.author.email }}
 * I love technology and I love blogging. My blog is about all things tech.
 * If you are a coder, you can check out [my Github profile](https://github.com/baidut/)
 * You can follow me on Twitter

I hope you enjoy this site. Thank you for your visit!

<!-- About this blog, about the posts -->

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
