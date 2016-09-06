---
layout: post
title: Projects and Research Experiences
permalink: /projects/
---
<ul>
  <li><strong><a href="#force_control">High-Precision Polishing Tool with the Ability to Control Machining Forces</a></strong></li>
  <li><strong><a href="#rescue_sos">SOS rescue robot</a></strong></li>
  <li><strong><a href="#data_board">Modular data acquisition and motor control board (Patented)</a></strong></li>
  <li><strong><a href="#thermal_camera">Thermal camera by TPA81 infrared sensor, Arduino and ROS framework</a></strong></li>
  <li><strong><a href="#khayyam_robot">Khayyam rescue robot</a></strong></li>
  <li><strong><a href="#time_server">Time and date server by ARM microcontroller</a></strong></li>
  <li><strong><a href="#bowling">Bowling Robot</a></strong></li>
  <li><strong><a href="#gimbal">Two axis gimbal prototype</a></strong></li>
  <li><strong><a href="#linefollower">Line follower robot & Solar car</a></strong></li>

  <br>
<ul>

<ul>
  {% for post in site.posts %}
    {% if post.permalink == "projects/force_control" %}
      <li>
        <hr> <strong> <a id="force_control" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/rescue_sos" %}
      <li>
        <hr> <strong> <a id="rescue_sos" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/data_board" %}
      <li>
        <hr> <strong> <a id="data_board" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/khayyam_robot" %}
      <li>
        <hr> <strong> <a id="khayyam_robot" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/thermal_camera" %}
      <li>
        <hr> <strong> <a id="thermal_camera" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/time_server" %}
      <li>
        <hr> <strong> <a id="time_server" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/bowling_robot" %}
      <li>
        <hr> <strong> <a id="bowling" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/gimbal" %}
      <li>
        <hr> <strong> <a id="gimbal" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

  {% for post in site.posts %}
    {% if post.permalink == "projects/linefollower_robot" %}
      <li>
        <hr> <strong> <a id="linefollower" href="{{ post.url }}">{{ post.title }}</a> </strong> <hr>
        <br>
        {{ post.content }}
        <br>
      </li>
    {% endif %}
  {% endfor %}

</ul>
