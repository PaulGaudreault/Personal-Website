---
layout: default
title: About
---

## Team
The following people are members of our team:
{% for team_member in site.team_members %}
 - {{ team_member.name }}, role: {{ team_member.role }}
{% endfor %}
