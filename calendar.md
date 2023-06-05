---
layout: page
title: Lectures
description: Listing of course lectures, with links to slides
nav_order: 1
---

# Calendar

{% assign modules = site.modules | where: "year", "2023" %}
{% for module in modules %}
{{ module }}
{% endfor %}
