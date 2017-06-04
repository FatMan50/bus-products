---
layout: default
title: "Lets Roll"
description: "The Abide Bus is the one and only bus you will ever need."
img:
 - image_path: /images/bus-and-the-bridge.jpg
images:
  - image_path: /images/bus-at-the-doctors.jpg
    title: The Bus is More than you can handle!  
  - image_path: /images/sang-wich.jpg
    title: The Bus is what the women all want!  
  - image_path: /images/in-da-bus-wide.jpg
    title: The Bus is the Queen of LA!  
  - image_path: /images/bus-at-the-beach.jpg
    title: The Bus has nothing to gain and nothing to lose!  
price-cad: 1798.
price-pdf: 999.
---

# Let it Roll Product!
{% for img in page.img %}
<img src="{{ site.url }}{{ img.image_path }}" alt="{{ page.title }}">
{% endfor %}

<div class="product-rule">
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><a href="{{ image.image_path }}" data-lightbox="image-1" data-title="{{ image.title }}" title="{{ image.title }}"><img src="{{ image.image_path }}" alt="{{ image.title}}"/></a></li>
  {% endfor %}
</ul>
</div>


### Description
<p class="editable">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p class="editable">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

## CAD Price: ${{ page.price-cad }}

## PDF Price: ${{ page.price-pdf }}
