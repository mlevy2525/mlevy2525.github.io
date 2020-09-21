---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research utilizes a mixture of computer vision and robotics approaches to try and make robots more useful in the real world. More speciaically, I focus on issues of dynamic robotics, how robots act in the world where objects move irrespective of the robot's actions. 

My long term goal is to create a method for using robots to solve complex multi step tasks which currently require specialists. Some examples of this are fully functioning cooking robots or robots that can actually perform steps of a surgery.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
