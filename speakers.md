---
layout: page
title: Instructors
description: A listing of all the course instructors.
nav_order: 2
---

# Instructors

{% assign instructors = site.speakers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

