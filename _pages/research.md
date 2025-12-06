---
layout: single
title: "Research"
permalink: /research/
author_profile: false
classes: wide
header:
  overlay_image: /header-banner.jpg
  overlay_filter: 0.5
---

<style>
.page__content {
  max-width: 1200px !important;
}

.research-intro {
  text-align: center;
  margin-bottom: 3rem;
}

.research-intro h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
  color: #2c3e50;
}

.research-intro p {
  color: #666;
  font-size: 1.1rem;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 3rem 2rem;  /* Vertikal 3rem, Horizontal 2rem */
  margin-bottom: 3rem;
}

.research-card {
  display: grid;
  grid-template-rows: 280px auto auto;  /* Feste Höhen für Alignment */
  text-align: center;
}

.research-card-image {
  width: 100%;
  height: 280px;  /* Feste Höhe */
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
  background: transparent;
}

.research-card img {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  object-fit: contain;
  display: block;
  margin: 0 auto;
}

.research-card h3 {
  font-size: 1.4rem;
  font-weight: 600;
  color: #1a1a1a;
  margin: 0 0 1rem 0;
  line-height: 1.3;
  min-height: 3.6em;  /* Platz für 2-3 Zeilen */
  display: flex;
  align-items: center;
  justify-content: center;
}

.research-card p {
  color: #555;
  line-height: 1.6;
  font-size: 0.95rem;
  margin: 0;
}

@media (max-width: 768px) {
  .research-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .research-card-image {
    height: 240px;
  }
  
  .research-card h3 {
    min-height: auto;
  }
}
</style>

<div class="research-intro">
  <h1>Research Projects</h1>
  <p>A collection of research projects results and applications.</p>
</div>

<div class="research-grid">

<!-- Project 1 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/research/roadside.jpg" alt="Roadside Safety">
  </div>
  <h3>Robust roadside safety pedestrian tracking</h3>
  <p>Event-based sensing for day and night pedestrian tracking and vehicle classification at the edge. Local, low-power TinyAI on the gantry.</p>
</div>

<!-- Project 2 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/research/robot-sensorimotor.jpg" alt="Robot Sensorimotor">
  </div>
  <h3>Robot sensorimotor control</h3>
  <p>Embedded sensorimotor control loop using spiking neural networks for a goal perception-action-cycle. Neuromorphic sensing combined with embedded spiking neural networks for mobile robot kinematics and manipulation control.</p>
</div>

<!-- Project 3 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/research/robot-bionic.jpg" alt="Robot Bionic">
  </div>
  <h3>Robot bionic trajectory stabilization</h3>
  <p>Bee-like trajectory stabilization algorithm using neuromorphic sensing and embedded processing. Optic flow and displacement to center adapt robot's trajectory.</p>
</div>

<!-- Project 4 -->
<div class="research-card">
  <div class="research-card-image">
    <img src="/images/research/multisensory-fusion.jpg" alt="Multisensory Fusion">
  </div>
  <h3>Multisensory fusion for scene understanding</h3>
  <p>Neuromorphic sensing fused with depth sensors. Each event from the neuromorphic camera has a depth value coded in the reference system of the embedded system.</p>
</div>

</div>