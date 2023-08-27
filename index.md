---
layout: about
title: Programming Games Syllabus
permalink: "/"
---



<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ site.baseurl }}{{ post.url }}">
     {{ post.title }}
     </a>
    </p>
  {% endfor %}
</ul>

<br>
<p><a href='/about'>About this site</a></p>
 
![Purchase College clock tower]({{ site.baseurl }}/assets/img/clock.jpg)
