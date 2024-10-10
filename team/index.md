---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team consists of members from both the University of Maryland and the University of Arizona. Find out more about our research group here.

## Principal Investigator

{% include list.html data="members" component="portrait" filters="role: pi" %}

## Administration and Research Staff

{% include list.html data="members" component="portrait" filters="role: (coordinator|researcher)" %}

## Students

{% include list.html data="members" component="portrait" filters="role: (phd|undergrad)" %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html background="images/background.jpg" dark=true %}

Our team thrives on collaboration across disciplines and institutions, bringing together innovative ideas and diverse perspectives to tackle the challenges of photonic quantum systems. Whether you’re interested in joining us or learning more about our research, we encourage you to explore the exciting work we’re doing.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/hike1.JPG" %}
{% include figure.html image="images/group1.jpg" %}
{% include figure.html image="images/hike2.JPG" %}

{% endcapture %}

{% include grid.html style="square" content=content %}