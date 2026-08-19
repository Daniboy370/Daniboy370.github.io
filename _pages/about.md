---
layout: about
title: about
permalink: /
subtitle: ""

profile:
  align: right
  image: Profile-0.png
  image_circular: false
  style: "max-width: 120px;"  # Visual size on screen

selected_papers: true
social: false

news: true # <--- THIS ENABLES THE TICKER ON ABOUT.MD
announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

<!-- <style>
  .profile img {
    max-width: 180px !important; /* Adjust this number to whatever size you prefer */
    height: auto;
  }
</style> -->

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

My research focuses on end-to-end **Guidance, Navigation, and Control (GNC)** for autonomous aerial systems, with particular emphasis on the interface between **state estimation** and **feedback control**. A central question underlying my work is 

_"How uncertainty in the estimated state propagates through the control hierarchy and ultimately affects closed-loop stability and precision?"_.

By pioneering **estimation-aware** control frameworks, I build **unified GNC pipelines** that explicitly account for sensor noise and estimation uncertainties across multiple levels of the GNC stack—from high-bandwidth attitude stabilization to trajectory tracking and higher-level autonomous decision making. 

By integrating sensing, estimation, and control rather than treating them as independent components, my research aims to establish principled operating bounds under sensing, actuation, and environmental constraints, unlocking precise and resilient autonomy in complex, GNSS-denied environments.

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
