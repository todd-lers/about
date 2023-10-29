
---
layout: default
---


images:
  - image_path: pics/events/2023 Hyde and Holland Park trip/IMG_7401.jpeg
   title: Hyde and Holland Park trip 1
  - image_path: pics/events/2023 Hyde and Holland Park trip/IMG_7356.jpeg
    title: Hyde and Holland Park trip 2


---

<ul class="current">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
