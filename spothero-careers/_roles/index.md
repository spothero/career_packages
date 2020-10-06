---
layout: page
title: Roles
---

<ul>
{% for packages in site.data.packages.people %}
{% assign rank = packages[1] %}
  <li>
    <a href="rank{{rank.rank}}.html">{{rank.title}}</a>
    {{rank.scope}}
  </li>
{% endfor %}
</ul>
