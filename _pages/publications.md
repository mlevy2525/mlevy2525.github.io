---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

My research utilizes a mixture of computer vision and robotics approaches to try and make robots more useful in the real world. 

In the past I worked on dynamic robotics more specifically focusing on how robots should act in the world where objects move irrespective of the robot's actions. 

Currently my work focuses on how we can train robots to complete tasks with better data efficency. 

My long term goal is to teach robots how to solve tasks from videos of humans in the wild. This will enable training without the expense of collecting data specifically on a robot.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
