---
layout: single
title: "Team"
permalink: /team/
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

.team-intro {
  text-align: left;
  margin-bottom: 3rem;
}

.team-intro h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
  color: #2c3e50;
}

.team-intro p {
  color: #666;
  font-size: 1.1rem;
}

.team-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 3rem 2rem;
  margin-bottom: 3rem;
}

.team-member {
  text-align: left;
}

.team-member-image {
  width: 100%;
  max-width: 500px;
  max-height: 500px;
  margin: 0 auto 1.5rem;
  border-radius: 12px;  /* Abgerundete Ecken statt rund */
  overflow: hidden;
  background: #f5f5f5;
  display: flex;
  align-items: down;
  justify-content: left;
  border: 4px solid #e1e4e8;
  transition: border-color 0.3s, transform 0.3s;
}

.team-member-image:hover {
  border-color: #0066cc;
  transform: scale(1.05);
}

.team-member-image a {
  width: 100%;
  height: 100%;
  display: block;
}

.team-member-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.team-member h3 {
  margin: 0;
  font-size: 1.3rem;
  font-weight: 600;
}

.team-member h3 a {
  color: #2c3e50;
  text-decoration: none;
  transition: color 0.3s;
}

.team-member h3 a:hover {
  color: #0066cc;
}

.team-member .role {
  color: #777;
  font-size: 0.95rem;
  margin-top: 0.5rem;
}

@media (max-width: 1024px) {
  .team-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 640px) {
  .team-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .team-member-image {
    max-width: 1000px;
    height: 550px;
  }
}
</style>

<div class="team-grid">

<!-- Team Member -->
<div class="team-member">
  <div class="team-member-image">
    <a href="https://www.th-nuernberg.de/en/faculties/in/research/cognitive-neurocomputing/">
      <img src="/images/team/spices-lab.jpg" alt="SPICES Lab" width="280" height="410">
    </a>
  </div>
  <h3><a href="https://www.th-nuernberg.de/en/faculties/in/research/cognitive-neurocomputing/">SPICES Lab</a></h3>
</div>

<!-- Team Member -->
<div class="team-member">
  <div class="team-member-image">
    <a href="https://www.iis.fraunhofer.de/de/ff/kom/ki/snn.html">
      <img src="/images/team/ncs.jpg" alt="NCSLab" width="241" height="410">
    </a>
  </div>
  <h3><a href="https://www.iis.fraunhofer.de/de/ff/kom/ki/snn.html">NCS Lab</a></h3>
</div>

<!-- Team Member -->
<div class="team-member">
  <div class="team-member-image">
    <a href="https://neurocomp-labs.de/">
      <img src="/images/team/neurocomp.jpg" alt="Neuro Comp Nord Bayern Labs" width="410" height="410">
    </a>
  </div>
  <h3><a href="https://neurocomp-labs.de/about-us/">NeuroComp Nord Bayern Labs</a></h3>
</div>


</div>
