---
layout: page
title: Vegånia - Ravintolat
permalink: /ravintolat/
main-menu: Ravintolat
main-menu-weight: 1
description: "Vegånia levittäytyy myös Vanhan Suurtorin ulkopuolelle. Turkulaiset yhteistyöravintolamme tarjoavat elokuun ensimmäisen viikon aikana 1.-5.8. ravintoloissaan tapahtuman nimikkoannoksen tai -menun."
---

***

[Vegånia-nimikkoannoksia](/ravintolat/menu/) löytyy seuraavista ravintoloista

{% include logocards.html data=site.data.nimikkoannos_ravintolat %}

***

![Ravintolakartta]({{ site.url }}/images/kartta.jpg)

<ul class="list-inline">
  {% for venue in site.data.kartta_ravintolat %}
    {% include map_location.html venue=venue %}
  {% endfor %}
</ul>

***

Ravintoloiden [nimikkoannokset ja menut](/ravintolat/menu/).
