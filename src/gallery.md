---
layout: layouts/page.njk
title: Test gallery
gallery:
- "/images/demo-image-1.jpg"
- "/images/demo-image-2.jpg"
- "/images/00000portrait_00000_burst20191210143228651.jpg"
- "/images/social-share.jpg"
templateEngineOverride: njk,md

---
{% for item in gallery %}
  <img src={{item}} alt=""/>
{% endfor %}