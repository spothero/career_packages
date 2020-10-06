---
layout: page
title: Engineer 2
---

<h3>People</h3>
<ul>
{% assign package = site.data.packages.people.rank2 %}
  <li>
      {{ package.title }}
      {{ package.scope }}
      {{ package.rank }}
  </li>
</ul>

<h3>Engineering</h3>
{% assign engineering = site.data.packages.engineering.rank2 %}

Sound-Bite: {{ engineering.soundbite }}
Engineering/ Writing Code: {{ engineering.engineering.writing_code }}
Education / Code Review: {{ engineering.education.code_review }}
