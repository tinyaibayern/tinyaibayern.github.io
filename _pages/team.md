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
  text-align: center;
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
  text-align: center;
}

.team-member-image {
  width: 100%;
  max-width: 250px;
  height: 250px;
  margin: 0 auto 1.5rem;
  border-radius: 12px;  /* Abgerundete Ecken statt rund */
  overflow: hidden;
  background: #f5f5f5;
  display: flex;
  align-items: center;
  justify-content: center;
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
    max-width: 200px;
    height: 200px;
  }
}
</style>

<div class="team-grid">

<!-- Team Member -->
<div class="team-member">
  <div class="team-member-image">
    <a href="https://www.th-nuernberg.de/en/faculties/in/research/cognitive-neurocomputing/">
      <img src="/images/team/spices-lab.jpg" alt="SPICES Lab">
    </a>
  </div>
  <h3><a href="https://www.th-nuernberg.de/en/faculties/in/research/cognitive-neurocomputing/">SPICES Lab</a></h3>
</div>

</div>