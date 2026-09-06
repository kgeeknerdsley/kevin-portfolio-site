---
title: "Gravity Well"
excerpt: "A computer vision tracking system tracing balls around a funnel"
project_type: professional 
header:
  teaser: /assets/images/gravitywell-bi/teaser.png
  overlay_image: /assets/images/gravitywell-bi/overlay.png
  overlay_filter: 0.3
gallery:
  - url: /assets/images/gravitywell-bi/photo1.png
    image_path: /assets/images/gravitywell-bi/photo1.png
    alt: "photo 1"
  - url: /assets/images/gravitywell-bi/photo2.png
    image_path: /assets/images/gravitywell-bi/photo2.png
    alt: "photo 2"
  - url: /assets/images/gravitywell-bi/photo3.png
    image_path: /assets/images/gravitywell-bi/photo3.png
    alt: "photo 3"
---

## Overview
The Gravity Well is part of the [The Franklin Institute's Wondrous Space](https://fi.edu/en/press-room/press-releases/2023/wondrous-space) exhibit in Philadelphia, PA. I worked on this as the Lead Embedded Systems Engineer at [Beaudry Interactive](https://www.binteractive.com/post/wondrous-space).

Guests approach the Gravity Well and roll a ball into the funnel, in order to show a visual representation of how gravity affects objects in its sphere of influence. The computer vision system is tracking all balls present on the funnel, passing positional data to the game system for visual display. Each ball's position is tracked with a persistent identifier, as well as detecting and handling collisions between balls.

## Photos
{% include gallery caption="Photos of the Gravity Well." %}

## Contributions
- Design and implementation of tracking system
    - Ball persistent IDs and positioning
    - Calibration routines for setup and maintenance
- Installation and post-opening support

## Credits
More about the full project on [Beaudry Interactive's website](https://www.binteractive.com/post/dino-quest-re-imagined).