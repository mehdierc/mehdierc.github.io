---
layout: post
title:  "A model learning approach for General video game playing (GVGP) - (in preparation)"
date:   2016-09-04 15:21:00
permalink: projects/learning
---

{% include image.html url="/images/learning-ggp.jpg" caption="" width=500 align="center" %}
<p align="justify">
Precise decision making in games has always been one of the complex and exciting problems in artificial intelligence. General video game playing (GVGP) is a new branch of artificial intelligence, and its purpose is to design agents who can carry out intelligent behavior in every unknown environment. Two of the biggest problems of recently introduced algorithms are the assumption of availability of an exact model of the world (for conducting the search) and performing the search in an online way (not using previous experiences).
In this research, we tried to eliminate these two problems with introducing an offline method for learning a model of the world. Actor attempts to learn the model of the environment of a specific game, by repeating game and gaining experience. In each play, the player uses the updated model and after each game, the model will be updated. The final model is general and can be utilized in every model based search algorithm.
</p>
