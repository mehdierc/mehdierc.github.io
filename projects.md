---
layout: post
title: Projects and Research Experiences
permalink: /projects/
---
<ul>

  <li><strong><a href="#roboasist">Design and implementation of a differential drive mobile robot for SLAM and map-based indoor navigation</a></strong></li>
  <li><strong><a href="#force_control">High-Precision Polishing Tool with the Ability to Control Machining Forces</a></strong></li>
  <li><strong><a href="#rescue_sos">SOS rescue robot</a></strong></li>
  <li><strong><a href="#intern_industry">Water pumping station automation, summer internship</a></strong></li>
  <li><strong><a href="#learning">A model learning approach for General video game playing (GVGP) - (in preparation)</a></strong></li>
  <li><strong><a href="#data_board">Modular data acquisition and motor control board (Patented)</a></strong></li>
  <li><strong><a href="#thermal_camera">Thermal camera by TPA81 infrared sensor, Arduino and ROS framework</a></strong></li>
  <li><strong><a href="#khayyam_robot">Khayyam rescue robot</a></strong></li>
  <li><strong><a href="#time_server">Time and date server by ARM microcontroller</a></strong></li>
  <li><strong><a href="#bowling">Bowling Robot</a></strong></li>
  <li><strong><a href="#gimbal">Two axis gimbal prototype</a></strong></li>
  <li><strong><a href="#linefollower">Line follower robot & Solar car</a></strong></li>

  <br>
</ul>

<ul>
  {% for post in site.posts %}
    {% if post.permalink == "projects/roboasist" %}
      <li>
        <hr> <strong id="roboasist"> {{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/force_control" %}
      <li>
        <hr> <strong id="force_control">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/rescue_sos" %}
      <li>
        <hr> <strong id="rescue_sos">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/intern_industry" %}
      <li>
        <hr> <strong id="intern_industry">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/learning" %}
      <li>
        <hr> <strong id="learning">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/data_board" %}
      <li>
        <hr> <strong id="data_board">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/khayyam_robot" %}
      <li>
        <hr> <strong id="khayyam_robot">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/thermal_camera" %}
      <li>
        <hr> <strong id="thermal_camera">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/time_server" %}
      <li>
        <hr> <strong id="time_server">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/bowling_robot" %}
      <li>
        <hr> <strong id="bowling">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/gimbal" %}
      <li>
        <hr> <strong id="gimbal">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/linefollower_robot" %}
      <li>
        <hr> <strong id="linefollower">{{ post.title }} </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

</ul>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-83932428-1', 'auto');
  ga('send', 'pageview');

</script>
