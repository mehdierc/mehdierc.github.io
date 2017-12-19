---
layout: post
title:  "Line follower robot & Solar car"
date:   2016-09-04 20:21:00
permalink: projects/linefollower_robot
slidename: linefollowerbot
---

{% include image.html url="/images/linefollower-1.jpg" caption="" width=560 align="center" %}
<p align="justify">
I was robotics and electronics tutor for the secondary level students in a student research center. In my class, we created a line follower robot and a small solar car.
<br><br>
<b>See the following video:</b>
<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/_BIdpkssrZg" frameborder="0" allowfullscreen></iframe>
</p>
</p>
<b>Photo Gallery:</b>
<br>
<div class="w3-content" style="max-width:560px">
  <img class="slide_{{ page.slidename }}" src="/images/linefollower-3.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/linefollower-2.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/linefollower-sch-e.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/linefollower-pcb-e.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/solarcar-e.jpg" style="width:100%">
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
