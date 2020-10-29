---
layout: page
title: Design & Drawing
description: Design & Drawing Service
name: design_draw
permalink: "/design_draw/"
images:
  - image_path: /images/design/home.jpg
    title: Home Design
  - image_path: /images/design/kit.jpg
    title: Kitchen Design
  - image_path: /images/design/kitchen.jpg
    title: Kitchen layout
  - image_path: /images/design/triangle.jpg
    title: Ergonomic Kitchen Design
---
<ul class="photo-gallery">
  {% for image in page.images %}
    <li>
    <img src="{{ image.image_path }}" alt="{{ image.title }}">
    </li>
    {% endfor %}
</ul>
