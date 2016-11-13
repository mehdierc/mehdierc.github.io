---
layout: post
title:  "Bowling Robot"
date:   2016-09-04 14:59:00
permalink: projects/bowling_robot
slidename: bowlinger
---

{% include image.html url="/images/bowling-2.jpg" caption="" width=560 align="center" %}

<p align="justify">
I have interested in robotics since childhood. I made this robot at the age of fourteen, and it was able to play bowling as an intelligent bowling ball, detect and hit pins! This robot was working with transistors, electronic relays, and simple digital gates and I can remember that I designed and created most of its circuits and PCBs by hand. :)
<br><br>
<b>See the following video:</b>
<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/J4qfe105n2k" frameborder="0" allowfullscreen></iframe>
</p>
<b>Photo Gallery:</b>
<br>

<div class="w3-content" style="max-width:560px">
  <img class="slide_{{ page.slidename }}" src="/images/bowling-m2.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/bowling-m1.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/bowling-3.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/bowling-4.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/bowling-1.jpg" style="width:100%">
</div>

<div class="w3-center">
  <div class="w3-section">
    <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(-1)">❮ Prev</button>
    <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(1)">Next ❯</button>
  </div>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">1</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">2</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">3</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">4</button>
  <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">5</button>
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
