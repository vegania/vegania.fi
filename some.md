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

{% if site.instagram.username %}
## instagram

<div id="instafeed"></div>

<script src="{{ "/js/instafeed.min.js" | prepend: site.baseurl }}" type="text/javascript"></script>

<script type="text/javascript">
    var userFeed = new Instafeed({
        get: 'user',
        userId: '4449418099',
        accessToken: '4449418099.99230d3.48dceca4871b4085a22ba3e66108926f',
        get: 'user',
        sortBy: 'most-recent'
    });
    userFeed.run();
</script>
{% endif %}
