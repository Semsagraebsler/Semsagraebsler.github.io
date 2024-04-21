---
layout: post
title: Gründungsversammlung
date: 2024-04-16 17:00:00+0200
description: Eindrücke  unserer Gründungsversammlung
tags: information bilder
categories: Offizielles
thumbnail: assets/img/2024-04-16_Gruendungsversammlung/PXL_20240416_163511058.jpg
images:
  compare: true
  slider: true
---

Hier ein paar Eindrücke unserer Gründungsversammlung


## Impressionen
<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
{% for image in site.static_files %}
    {% if image.path contains 'img/2024-04-16_Gruendungsversammlung' %}
      {% capture img_url %}{{ image.path | remove_first: "/"}}{% endcapture %}
  <swiper-slide>{% include figure.liquid loading="eager" path=img_url class="img-fluid rounded z-depth-1" %}</swiper-slide>
    {% endif %}
{% endfor %}
</swiper-container>
