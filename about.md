---
layout: default
lesson-example: "https://carpentries.github.io/lesson-example/"
title: About
---

## Project 

{{ site.description }}

## Team

The following people are members of the research team:
{% for team_member in site.team_members %}
- {{ team_member.name}}, role: {{team_member.role }}
{% endfor %}
