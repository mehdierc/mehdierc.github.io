---
layout: post
title:  "SOS rescue robot"
date:   2016-09-04 23:39:20
permalink: projects/rescue_sos
---
{% include image.html url="/images/sos-2.jpg" caption="" width=560 align="center" %}
<br>
{% include image.html url="/images/sos-logo.jpg" caption="" width=250 align="left" %}
<p align="justify">
I’m head of SOS robotic team that is working in the mechanical department of the Isfahan University of Technology, and its primary focus is on rescue robots. Our team consists of 9 people, and we have two robots including one ground vehicle and one Quad-rotor. Our ground vehicle is designed based on a mechanism consists of five main parts that provide three different configurations. These five elements are four independent moving” crawler arms and one body. In software, we mostly focus on SLAM algorithms and robot AI engine. Our goal is to develop a robot with a reliable and robust system with hope to success in helping humans in real disaster sites.
<br>
An operator controls the robot via a teleportation process, so the control operation is not entirely autonomous right now. We are developing the control method to make it fully independent. Connection between the robot and operator station is based on the following diagrams:
<br>
{% include image.html url="/images/sos-d1.jpg" caption="" width=650 align="center" %}
<br>
{% include image.html url="/images/sos-d2.jpg" caption="" width=650 align="center" %}
<br>

There is a PC inside the robot that processes images, the output of sensors, controls the actuators and runs the SLAM algorithm. As shown in the diagram, the process outputs and control feedbacks are sent to the operator station via a wireless connection, and the operator observes them is a GUI and operates the robot using a joystick and keyboard.
<br><br>

<b>Photo Gallery:</b>
<br>

<div class="w3-content" style="max-width:560px">
  <img class="slide_{{ page.slidename }}" src="/images/sos-1.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/sos-3.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/sos-4.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/sos-5.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/sos-6.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/sos-7.jpg" style="width:100%">
</div>

<div class="w3-center">
  <div class="w3-section">
    <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(-1)">❮ Prev</button>
    <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(1)">Next ❯</button>
  </div>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">1</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">2</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(3)">3</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(4)">4</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(5)">5</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(6)">6</button>
</div>

<script>
var slideIndex_{{ page.slidename }} = 1;
showDivs_{{ page.slidename }}(slideIndex_{{ page.slidename }});

function plusDivs_{{ page.slidename }}(n) {
  showDivs_{{ page.slidename }}(slideIndex_{{ page.slidename }} += n);
}

function currentDiv_{{ page.slidename }}(n) {
  showDivs_{{ page.slidename }}(slideIndex_{{ page.slidename }} = n);
}

function showDivs_{{ page.slidename }}(n) {
  var i;
  var x = document.getElementsByClassName("slide_{{ page.slidename }}");
  var dots = document.getElementsByClassName("demo_{{ page.slidename }}");
  if (n > x.length) {slideIndex_{{ page.slidename }} = 1}
  if (n < 1) {slideIndex_{{ page.slidename }} = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
     dots[i].className = dots[i].className.replace(" w3-red", "");
  }
  x[slideIndex_{{ page.slidename }}-1].style.display = "block";
  dots[slideIndex_{{ page.slidename }}-1].className += " w3-red";
}
</script>
</p>
