---
layout: page
show_meta: false
title: "한기대에서 교통을 이용하는 법은?"
subheadline: "What is the good way to use a traffic in koreatech?"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/traffic/"
---
<ul>
    {% for post in site.categories.traffic %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>


