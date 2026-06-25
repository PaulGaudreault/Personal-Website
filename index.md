---
layout: home
title: "Home"
author: "Paul Gaudreault"
---
## Description
{{ site.description }}

{% assign lead=site.team_members | where: "role", "project lead" | first %}
The project is led by {{ lead.name }}
[See our full team](about#team)
