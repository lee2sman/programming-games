---
layout: about
title: Programming Games Syllabus
permalink: "/"
---



# ABOUT this site

This site features open educational resources for an introductory programming course Programming Games. This curriculum was developed for a general audience, with no background in programming, in order to teach the fundamentals of programming through making video games. This site and curriculum was developed by Lee Tusman, Assistant Professor of New Media and Computer Science at Purchase College, with the support of a Topol Faculty Development Award.

The class is taught in the language Lua, using the [LÖVE](https://love2d.org/) and [Pico-8](https://www.lexaloffle.com/pico-8.php) game engines.

Making a game is fun but lots of work! Students are expected to follow along, code throughout the week, and complete all assignments. There are three main game projects: an 80s/90s arcade style game, an adventure game, and a final game of their choice. The first 8 weeks of class cover LÖVE. Pico-8 will be taught in the following weeks. A student has their choice of framework for their final game assignment.

This site builds upon open source books, lesson plans and tutorials, cited. Mini workshops and projects are completed along the way, including building text adventure games and pong.

There are 15 classes, for a "semester-long" course, with one field trip class and one final projects presentations class.  

<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ site.baseurl }}{{ post.url }}">
     {{ post.title }}
     </a>
    </p>
  {% endfor %}
</ul>

 
<br/>
Curriculum by Lee Tusman. 

Website design adapted from: [Ashley Blewer](https://ashleyblewer.com), 2021 - 2022  
Lee Tusman 2023  
CC BY-NC  
Pico-8 gif by [REZ](http://www.chiptune.com/). 

See also &#8608; [site source code](https://github.com/lee2sman/programming-games).

![under construction]({{ site.baseurl }}/assets/img/construction.gif)

![Purchase College clock tower]({{ site.baseurl }}/assets/img/clock.jpg)
