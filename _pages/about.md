---
layout: about
title: about
permalink: /
subtitle: ""
---

profile:
  align: right
  image: Profile-0.png
  image_circular: false # crops the image to make it circular
  style: "max-width: 130px;"  # <-- Add this line! Adjust pixels to your liking (e.g., 150px, 180px, 200px)
    
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a Ph.D. researcher at the [Autonomous Navigation and Sensor Fusion Lab (ANSFL)](https://ansfl.marsci.haifa.ac.il/), led by Prof. [Itzik Klein](https://scholar.google.com/citations?user=uwjVBkIAAAAJ&hl=en) at the University of Haifa. I focus on **Guidance, Navigation, and Control (GNC)** for **aerial platforms**. 

My research bridges robust control theory, state estimation, and learning-based flight control to enable unmanned aerial platforms to operate with full autonomy in complex, GPS-denied environments—both indoors and outdoors.

---
### Research Interests
* **Agile and Robust GNC:** Trajectory optimization, robust and adaptive control, end-to-end autonomous navigation pipelines for aerial platforms.
* **Perception & State Estimation:** Vision-aided inertial navigation (VINS), multi-sensor fusion (IMU/Vision/LiDAR), and state estimation in GPS-denied environments.
* **Sim-to-Real & Robot Learning:** Photorealistic synthesis, physics-grounded simulation, and transfer learning for agile autonomous flight.


---

<div style="text-align: center; margin: 20px 0;">
  <video autoplay loop muted playsinline style="width: 100%; max-width: 800px; height: auto;">
    <source src="{{ '/assets/video/Quad_Chase_2.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-size: 0.85em; color: #666; margin-top: 6px;">
    <em>Two INDI-based, Estimation-Aware (ours) vs. nominal baseline, competing on tilted lemniscate path following.</em>
  </p>
</div>

<!-- <div style="text-align: center; margin: 20px 0;">
  <img src="{{ '/assets/img/Quad_Chase_2.gif' | relative_url }}" 
       alt="Autonomous Drone Flight Demo" 
       style="width: 100%; max-width: 640px; height: auto; border: none; outline: none;">
  <p style="font-size: 0.85em; color: #666; margin-top: 6px;">
    <em>Two INDI-based, Estimation-Aware (ours) vs. nominal baseline, competing on tilted lemniscate path following.</em>
  </p>
</div> -->

---
