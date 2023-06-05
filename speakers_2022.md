---
layout: page
title: Instructors
description: A listing of all the course instructors.
permalink: /2022/speakers/
parent: ICASSP 2022 SC1
grand_parent: Courses from Prior Years
nav_order: 2
---

# Instructors

{% assign instructors = site.speakers2022 | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

