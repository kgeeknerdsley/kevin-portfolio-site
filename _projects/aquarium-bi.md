---
title: "Virtual Aquarium Interactives"
excerpt: "Multiple computer vision interactive components, for fish drawings and playful lighting"
project_type: professional 
header:
  teaser: /assets/images/aquarium-bi/teaser.png
  overlay_image: /assets/images/aquarium-bi/overlay.png
  overlay_filter: 0.3
gallery:
  - url: /assets/images/aquarium-bi/photo1.png
    image_path: /assets/images/aquarium-bi/photo1.png
    alt: "photo 1"
  - url: /assets/images/aquarium-bi/photo2.png
    image_path: /assets/images/aquarium-bi/photo2.png
    alt: "photo 2"
  - url: /assets/images/aquarium-bi/photo3.png
    image_path: /assets/images/aquarium-bi/photo3.png
    alt: "photo 3"
---

## Overview
The Virtual Aquarium is part of the [Carnival Cruise Line's Currents](https://www.carnival-news.com/2024/02/22/inside-the-fun-currents-zone-on-carnival-jubilee-wows-guests-with-interactive-activations-including-seaquest-a-fun-sub-adventure) zone, aboard the Carnival Jubilee. I worked on this as the Lead Embedded Systems Engineer at [Beaudry Interactive](https://www.binteractive.com/post/currents-zone).

The Carnival Jubilee features the Currents interactive zone aboard the Carnival Jubilee, a 2-story deck area with a rotating schedule of multimedia and audiovisual experiences. In the Virtual Aquarium segment, guests are invited to design their own sea creatures via a digital kiosk, or by coloring in drawings that are scanned into the digital system. I designed the computer vision system which translates physical drawings to digital representations, once scanned into the system.

I also worked on a second computer vision component, which tracks guests from a bird's eye perspective of the space, enabling dynamic lighting in the space to be aware of guests' physical presence.

## Photos
{% include gallery caption="Photos of the Virtual Aquarium interactives." %}

## Contributions
- Design and implementation of optical image recognition software
    - Performs automatic classification of drawing type
    - Extracts image from scan, with tolerance towards wide variety of inputs
    - Passes cleaned-up image to digital system for use in interactive
- Implementation of thermal imaging computer vision system
    - Provides real-time positioning of guests to show control system

## Credits
More about the full project on [Beaudry Interactive's website](https://www.binteractive.com/post/dino-quest-re-imagined).