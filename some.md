---
layout: page
title: "Paikka nimeltä #Vegånia"
permalink: /some/
main-menu: "#Vegånia"
main-menu-weight: 7
description: "Vegånia muualla netissä: Instagram, Twitter ja Facebook"
---

<ul class="list-inline">
  {% if site.facebook.username %}
  <li class="list-inline-item">
    {% include icon-facebook.html username=site.facebook.username %}
  </li>
  {% endif %}
  {% if site.twitter.username %}
  <li class="list-inline-item">
    {% include icon-twitter.html username=site.twitter.username %}
  </li>
  {% endif %}
  {% if site.instagram.username %}
  <li class="list-inline-item">
    {% include icon-instagram.html username=site.instagram.username %}
  </li>
  {% endif %}
</ul>
