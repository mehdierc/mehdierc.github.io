---
layout: post
title:  "Khayyam rescue robot"
date:   2016-09-04 20:21:00
permalink: projects/khayyam_robot
slidename: khayyamrobot
---

{% include image.html url="/images/khayyamrobot-1.jpg" caption="" width=560 align="center" %}
<p align="justify">
  I made this robot when I was in high school. With this robot, I participated in thirteenth {% include link.html link="http://kharazmi.medu.ir/" caption="Kharazmi young competition" %} which I <b>ranked 1st</b> in rescue robot junior league. Khayyam robot can follow a line, detect colored sticks on the ground, avoid obstacles, detect slopes and scan areas that don’t have lines. In this project, I did a good job at digital electronics, PCB design and AVR microcontrollers.
  I named the robot Khayyam; Khayyam was a great Persian poet and mathematician, who I’m a big fan of his quatrains. Read some of his poets in English {% include link.html link="http://www.gutenberg.org/files/246/246-h/246-h.htm" caption="here" %} :)
  <br><br>
  <b>The following videos show the functionality of khayyam robot:</b>
  <p align="center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLInd2RCogBE-OL2MII0IHkX7qAzqBDRTf" frameborder="0" allowfullscreen></iframe>
  </p>
</p>
<b>Photo Gallery:</b>
<br>
<div class="w3-content" style="max-width:560px">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-3.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-2.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-4.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-5.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-6.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-7.jpg" style="width:100%">
  <img class="slide_{{ page.slidename }}" src="/images/khayyamrobot-me.jpg" style="width:100%">
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
