---
layout: default
title: "The Abide Bus"
description: "The Abide Bus is the one and only bus you will ever need."
image:
  feature: /images/abide-bus-2.jpg
images:
  - image_path: /images/inside-the-bus.jpg
    title: The Bus is beautiful!
  - image_path: /images/drivers-seat.jpg
    title: The Bus is beautiful!
  - image_path: /images/shoeless-bus.jpg
    title: The Bus is beautiful!
price: 1200.
price-cad: 1400.
price-pdf: 875.
plan-copy: "Bacon ipsum dolor amet short ribs bresaola rump sirloin. Beef ribs short ribs bacon pig, t-bone sirloin pork belly shankle chuck pork jowl turkey. Short loin beef turkey spare ribs, porchetta swine prosciutto andouille meatloaf shoulder pastrami ground round leberkas sirloin fatback. Short loin andouille frankfurter short ribs bresaola pork belly tri-tip beef prosciutto strip steak ham hock jerky pig bacon. Beef ribs tail ribeye hamburger pork corned beef alcatra ball tip. Beef bacon short loin drumstick hamburger biltong frankfurter doner boudin."
---

# This is the Abide Bus Product!

<img src="{{ site.url }}{{ page.image.feature }}" alt="{{ page.title }}">

<div class="product-rule">
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><a href="{{ image.image_path }}" data-lightbox="image-1" data-title="{{ image.title }}" title="{{ image.title }}"><img src="{{ image.image_path }}" alt="{{ image.title}}"/></a></li>
  {% endfor %}
</ul>
</div>


### Description

{{ page.plan-copy }}

## CAD Price: ${{ page.price-cad }}

## PDF Price: ${{ page.price-pdf }}
