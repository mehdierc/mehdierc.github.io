---
layout: post
title:  "Water pumping station automation, summer internship"
date:   2016-09-03 23:21:00
permalink: projects/intern_industry
slidename: industrialintern
---


{% include image.html url="/images/intern-1.jpg" caption="" width=560 align="center" %}
<p align="justify">
My summer internship was on the subject of industrial automation in Arghanon corporation (Industrial automation services).
I learned a lot of things about PLC programming, HMI design, and electrical panels.
I participated in a water pumping station project as an industrial automation technician. The project was about controlling four electromotors for filling a water tank, and my duty was HMI design and PLC programming for line pressure control.
  <br><br>
  <b>Photo Gallery:</b>
  <br>

  <div class="w3-content" style="max-width:560px">
    <img class="slide_{{ page.slidename }}" src="/images/intern-2.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-3.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-4.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-5.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-6.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-7.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-8.jpg" style="width:100%">
    <img class="slide_{{ page.slidename }}" src="/images/intern-9.jpg" style="width:100%">
  </div>

  <div class="w3-center">
    <div class="w3-section">
      <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(-1)">❮ Prev</button>
      <button class="w3-btn" onclick="plusDivs_{{ page.slidename }}(1)">Next ❯</button>
    </div>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(1)">1</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">2</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">3</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">4</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">5</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">6</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">7</button>
    <button class="w3-btn demo_{{ page.slidename }}" onclick="currentDiv_{{ page.slidename }}(2)">8</button>
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
