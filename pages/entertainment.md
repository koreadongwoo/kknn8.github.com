---
layout: page
show_meta: false
title: "학교에서 누릴 수 있는 문화생활을 알려드립니다."
subheadline: "You can find the entertainment in koreatech."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/entertainment/"
---
<ul>
    {% for post in site.categories.entertainment %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>


