---
layout: post
title:  "Modular data acquisition and motor control board (Patented)"
date:   2016-09-04 15:21:00
permalink: projects/data_board
---

{% include image.html url="/images/daq.jpg" caption="" width=350 align="center" %}
<p align="justify">
I'm head of robotic teams in the mechanical department of the Isfahan University of Technology for about three years. One of the hardware related problems of our teams was about reading rotary encoders and sending motor command in cases that a robot has a lot of actuators and motors. We wanted a small, cheap and reliable system for capturing all of the encoders data and sending motors commands simultaneously. I Invented a modular and extensible data acquisition board by using simple and cheap components that can satisfy all of our requirements. I patented this project in IRAN (Registration number: 70553). The system has one motherboard, and we can put expansion boards on top of the motherboard regarding our requirements. Each expansion board can connect to five motor driver and five rotary encoders. We can connect maximum four development board to one motherboard so that the system can support 20 motors and encoders concurrently.
{% include image.html url="/images/daq-2.jpg" caption="" width=350 align="center" %}
Each encoder input can support up to 100Khz frequency, and each motor driver can be connected through PWM pulse, I2C or RS232 protocol.
The motherboard can connect to a computer or other controller boards with a proprietary protocol through USB, RS232 or SPI.
This system also provides 20 Digital Input/Output, ten analog input, and three analog output.
</p>
