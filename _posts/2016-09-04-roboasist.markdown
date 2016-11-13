---
layout: post
title:  "Design and construction of a differential drive mobile robot with the ability to do SLAM and map-based indoor navigation - RoboAsist"
date:   2016-09-04 23:21:00
permalink: projects/roboasist
slidename: roboasist
---

{% include image.html url="/images/roboasist-1.jpg" caption="" width=300 align="center" %}
<p align="justify">
RoboAsist is a differential drive mobile robot similar to <a href="http://www.turtlebot.com/">Turtlebot</a>. I designed and constructed it from scratch in
<a href="http://armlab.iut.ac.ir/" target="_blank">Advance Robotic and Mechatronic Laboratory (ARMLab)</a> with the aim of research on mobile robots.
My B.Sc. thesis defined on this robot, and it was about studying the theory and practical implementation of Simultaneous Localization and Mapping (SLAM) and map-based indoor navigation.
Furthermore, I implemented a simple colored-object follower on RoboAsist, based on Camshift algorithm.
I named this robot RoboAsist because of its ultimate goal: Laboratory assistant robot.
<br><br>
You can see the results of my works in the following videos, and design and construction process in the following image gallery.
  <br><br>
  <b>See the following playlist:</b>
  <p align="center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLInd2RCogBE8swlqtt5NQNlp3xAXe-A31" frameborder="0" allowfullscreen></iframe>
  </p>

  <b>Photo Gallery:</b>
  <br>

  <div class="w3-content" style="max-width:560px">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-2.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-3.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-4.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-5.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-6.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-7.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-8.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-9.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-10.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-11.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/roboasist-12.jpg" style="width:100%">
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
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(7)">7</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(8)">8</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(9)">9</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(10)">10</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(11)">11</button>
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
