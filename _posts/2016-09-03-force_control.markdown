---
layout: post
title:  "High-Precision force control"
date:   2016-09-03 23:21:00
permalink: projects/force_control
slidename: forcecontrol
---


{% include image.html url="/images/force-device.jpg" caption="" width=560 align="center" %}
<p align="justify">
This project was a long-running project with a major problem related to repeatability and controllability. The system was using a load cell to provide force feedback, but the feedback was not enough because of malfunctioning and friction of mechanical parts. I found an innovative solution to the problem of the system by replacing the load cell with an hand-made high precision infrared distance sensor and correlating the end-effector force with the distance of a two moving parts of the system. I changed the whole embedded hardware and control software. Finally, the problem solved, and the system worked, but this time, five times more accurate than expected. If you are interested in this project, feel free to contact me for more information. 
  <br><br>
  <b>See the following video:</b>
  <p align="center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/f_KgYS94ypc" frameborder="0" allowfullscreen></iframe>
  </p>

  <b>Photo Gallery:</b>
  <br>

  <div class="w3-content" style="max-width:560px">
    <img class="slide_{{ page.slidename }}" src="/images/force-w.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/force-m.jpg" style="width:100%">
  </div>

  <div class="w3-center">
    <div class="w3-section">
      <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(-1)">❮ Prev</button>
      <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(1)">Next ❯</button>
    </div>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">1</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">2</button>
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
