---
layout: default
title: data
permalink: /data/
---

<ul>
{% for novels in site.data.end-19c-epi %}
 <li>
  <strong>{{ novels.title }}</strong>
 </li>
{% endfor %}
</ul>
