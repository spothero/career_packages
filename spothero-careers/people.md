---
layout: page
title: SpotHero People Package
---

People Package:

{% for role in site.roles %}
  {{role.title}}
  {{role.gdtrow}}
{%endfor%}
