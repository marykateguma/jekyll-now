---
layout: default
title: data
permalink: /data/
---

<ul>
{% for monument in site.data.mlab2 %}
 <li>
  <img src="{{ monument.form_image_b }}">
  <strong>{{ monument.name }}</strong>
 </li>
 {% endfor %}
 </ul>
 
<ul>
{% for novels in site.data.end-19c-epi %}
  <li>
  <strong>{{ novels.title }}</strong>
  </li>
 {% li %}
 </ul>
