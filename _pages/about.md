---
layout: about
title: about
permalink: /
subtitle: ""

profile:
  align: right
  image: Profile-0.png
  image_circular: false

<style>
  .profile img {
    max-width: 110px !important; /* Adjust this number to whatever size you prefer */
    height: auto;
  }
</style>

selected_papers: true
social: false
---


<!-- Custom Social Links Row -->
<div style="margin: 20px 0 30px 0; display: flex; justify-content: center; gap: 25px; flex-wrap: wrap; align-items: center;">

  <!-- Google Scholar -->
  <a href="https://scholar.google.com/citations?user=IX7q2uAAAAAJ" target="_blank" style="text-decoration: none; font-size: 1.6em;" title="Google Scholar">
    <i class="ai ai-google-scholar"></i>
  </a>

  <!-- ResearchGate -->
  <a href="https://www.researchgate.net/profile/Daniel-Engelsman-3" target="_blank" style="text-decoration: none; font-size: 1.6em;" title="ResearchGate">
    <i class="ai ai-researchgate"></i>
  </a>
  
  <!-- GitHub -->
  <a href="https://github.com/Daniboy370" target="_blank" style="text-decoration: none; font-size: 1.6em;" title="GitHub">
    <i class="fab fa-github"></i>
  </a>

  <!-- ORCID -->
  <a href="https://orcid.org/0000-0003-0689-1097" target="_blank" style="text-decoration: none; font-size: 1.6em;" title="ORCID">
    <i class="ai ai-orcid"></i>
  </a>

  <!-- Email -->
  <a href="mailto:dengelsm@campus.haifa.ac.il" target="_blank" style="text-decoration: none; font-size: 1.6em;" title="Email">
    <i class="fas fa-envelope"></i>
  </a>

</div>

I am a Ph.D. researcher at the [Autonomous Navigation and Sensor Fusion Lab (ANSFL)](https://ansfl.marsci.haifa.ac.il/), led by Prof. [Itzik Klein](https://scholar.google.com/citations?user=uwjVBkIAAAAJ&hl=en) at the University of Haifa. I focus on **Guidance, Navigation, and Control (GNC)** for **aerial platforms**. 

My research bridges robust control theory, state estimation, and learning-based flight control to enable unmanned aerial platforms to operate with full autonomy in complex, GPS-denied environments—both indoors and outdoors.

---
### Research Interests
* **Agile and Robust GNC:** Trajectory optimization, robust and adaptive control, end-to-end autonomous navigation pipelines for aerial platforms.
* **Perception & State Estimation:** Vision-aided inertial navigation (VINS), multi-sensor fusion (IMU/Vision/LiDAR), and state estimation in GPS-denied environments.
* **Sim-to-Real & Robot Learning:** Photorealistic synthesis, physics-grounded simulation, and transfer learning for agile autonomous flight.

---
<div style="text-align: center; margin: 20px 0;">
  <video autoplay loop muted playsinline style="width: 100%; max-width: 900px; height: auto;">
    <source src="{{ '/assets/video/Quad_Chase_2.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-size: 0.85em; color: #666; margin-top: 6px;">
    <em>Two INDI-based controllers; nominal (brown, baseline) vs. Estimation-Aware (green, ours), competing on a tilted lemniscate trajectory.</em>
  </p>
</div>
---
