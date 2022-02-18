---
title: "Mechatronics: ATVA Object Tracking"
excerpt: "Starting soon:\n Creating a turret-mounted camera for object tracking and pose estimation."
header:
  #image: /images/unsplash-gallery-image-1.jpg
  teaser: images/atva.png
author_profile: true
gallery:
  # - url: /images/panda.jpg
  #   image_path: images/panda.jpg
  #   alt: "placeholder image 1"
---

I will be creating the ATVA system (Anomaly-Tracking for Vision-Aversion), which consists of a helmet-mounted object tracking camera and the required sensors for *visual contact prevention*. Find the proposal here: [ATVA Proposal](/pdf/atva_proposal.pdf).

This project was inspired by the short film [096](https://www.youtube.com/watch?v=MEOZkf4imaM), which features [SCP-096](https://scp-wiki.wikidot.com/scp-096)—a humanoid monster that becomes aggressively distressed when its face is viewed. To prevent visual contact, a researcher creates the SCRAMBLE Goggles, which use facial recognition and local image scrambling to prevent military operatives from seeing SCP-096's face.

An IMU, IR-distance sensor, and the aforementioned camera will be used to track a fiducial marker and notify the user when it is entering their field of vision (FOV), as shown in the figure below.

![no-alignment]({{ site.url }}{{ site.baseurl }}/images/atva_fov.png)
The transformation from center of FOV to edge of FOV is critical to this project.

More info coming soon!