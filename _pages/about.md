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

I am a Ph.D. researcher at the [Autonomous Navigation and Sensor Fusion Lab (ANSFL)](https://ansfl.marsci.haifa.ac.il/), led by Prof. [Itzik Klein](https://scholar.google.com/citations?user=uwjVBkIAAAAJ&hl=en) at the University of Haifa. 

Focusing on coupled estimator-controller dynamics and adaptive planning horizons, my research develops end-to-end **Guidance, Navigation, and Control (GNC)** for self-contained aerial robotics. 

Early results demonstrate that such unified pipelines manage to bridge high-fidelity simulation with resource-constrained hardware, enabling prolonged indoor missions without sacrificing real-time state consistency.

<!-- <style>
  .profile img {
    max-width: 140px !important; /* Adjust this number to whatever size you prefer */
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


---
<div style="text-align: center; margin: 20px 0;">
  <video autoplay loop muted playsinline style="width: 80%; max-width: 900px; height: auto;">
    <source src="{{ '/assets/video/Quad_Chase_2.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p style="font-size: 0.85em; color: #666; margin-top: 6px;">
    <em>Two INDI-based controllers; nominal (brown, baseline) vs. Estimation-Aware (green, ours), competing on a tilted lemniscate trajectory.</em>
  </p>
</div>
---

**Open Questions I'm Exploring**

* **Uncertainty Propagation Across Time Scales**: How does state estimation uncertainty propagate across multi-rate GNC layers? Can we establish spatiotemporal mappings that inform every level of the hierarchy without bottlenecking trajectory planners?

* **High-Fidelity Sim-to-Real Generalization**: How can photorealistic rendering and high-fidelity physics engines enable zero-shot deployment under unmodeled environmental interactions? Can domain randomization combined with physics-informed learning guarantee bounded tracking error during real-world execution?

* **Guaranteed Safety Under Active Degradation**: How do we construct dynamic safety certificates when sensor availability and noise statistics degrade unannounced? Can we bound state extrapolation across platform dynamics and environmental disturbances during extreme dead reckoning?

---
