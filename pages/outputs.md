---
layout: page
title: Resultat
permalink: /outputs/
position: 4
feature-img: "assets/img/pexels/digi_D_o.jpeg"
tags: [Page]
---

 <div class="home">
    <style scoped>
       
    </style>
    <div id="main" class="call-out call-out_img">
        <h1> {{ site.header_text | default: "Change <code>header_text</code> in <code>_config.yml</code>"}} </h1>
    </div>
    {% capture _blog %}{% include blog/blog.liquid %}{% endcapture %}
    {{ _blog | split: " " | join: " "}}
</div>
