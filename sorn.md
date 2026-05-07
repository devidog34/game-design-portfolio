---
layout: default
title: S.O.R.N - Dev Singh
---

<style>
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 50px 24px 90px;
}

.breadcrumb {
  color: #7f8aa3;
  font-size: 13px;
  margin-bottom: 40px;
}

.breadcrumb a {
  color: #9aa4b2;
  text-decoration: none;
}

.hero {
  margin-bottom: 60px;
}

.kicker {
  color: #38ef7d;
  letter-spacing: 5px;
  text-transform: uppercase;
  font-size: 13px;
  font-weight: 800;
  margin-bottom: 14px;
}

.hero h1 {
  font-size: 56px;
  line-height: 1;
  margin: 0 0 24px;
  letter-spacing: -1px;
  color: #b855ff;
}

.hero p {
  color: #c7ccd6;
  font-size: 17px;
  line-height: 1.7;
  max-width: 780px;
}

.section {
  margin: 80px 0;
}

.section h2 {
  font-size: 28px;
  margin-bottom: 20px;
  letter-spacing: -0.5px;
}

.section p,
.section li {
  color: #aeb6c4;
  font-size: 16px;
  line-height: 1.8;
}

.video {
  width: 100%;
  height: 520px;
  border: none;
  border-radius: 10px;
  margin: 30px 0;
}

.image {
  width: 100%;
  border-radius: 10px;
  border: 1px solid #1f2937;
  margin-top: 20px;
}

.image-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 24px;
  margin-top: 24px;
}

.beat {
  background: #111827;
  border: 1px solid #1f2937;
  border-radius: 12px;
  padding: 28px;
  margin: 34px 0;
}

.beat-number {
  color: #38ef7d;
  text-transform: uppercase;
  letter-spacing: 4px;
  font-size: 12px;
  font-weight: 800;
  margin-bottom: 8px;
}

.beat h3 {
  font-size: 30px;
  margin: 0 0 18px;
  color: #eaeaea;
}

.callout-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
  margin-top: 24px;
}

.callout {
  background: #0b0f17;
  border: 1px solid #1f2937;
  border-radius: 10px;
  padding: 18px;
}

.callout h4 {
  color: #7f8aa3;
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: 12px;
  margin: 0 0 8px;
}

.back {
  display: inline-block;
  margin-top: 60px;
  color: #60a5fa;
  text-decoration: none;
  font-weight: 600;
}

@media (max-width: 768px) {
  .hero h1 {
    font-size: 38px;
  }

  .video {
    height: 260px;
  }

  .image-grid,
  .callout-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="container">

  <div class="breadcrumb">
    <a href="./index.html">Projects</a> / S.O.R.N
  </div>

  <div class="hero">
    <div class="kicker">Level 2 · Unreal Engine 5 · Level Designer</div>
    <h1>S.O.R.N - The Lab</h1>
    <p>
      A level focused on encounter pacing, player routing, combat pressure,
      and testing the player in a tighter enviornment than in the first level of S.O.R.N.
    </p>
  </div>

  <!-- MAIN VIDEO -->
  <div class="section">
    <h2>Level Playthrough</h2>
    <iframe class="video"
      src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID?autoplay=0&controls=1"
      allowfullscreen>
    </iframe>
  </div>

  <!-- OVERVIEW -->
  <div class="section">
    <h2>Level Overview</h2>
    <p>
      S.O.R.N is a sci-fi level design project built around guiding the player through
      a high-tension environment while escalating combat encounters and narrative reveals.
      The goal was to create a space that felt purposeful, readable, and cinematic while
      still supporting strong moment-to-moment gameplay.
    </p>

    <div class="callout-grid">
      <div class="callout">
        <h4>Role</h4>
        <p>Level Designer</p>
      </div>

      <div class="callout">
        <h4>Engine</h4>
        <p>Unreal Engine 5</p>
      </div>

      <div class="callout">
        <h4>Focus</h4>
        <p>Player Flow, Encounters, Cinematic Pacing</p>
      </div>
    </div>
  </div>

  <!-- LEVEL GOALS -->
  <div class="section">
    <h2>Level Goals</h2>
    <ul>
      <li>Guide the player naturally through the environment using lighting, layout, landmarks, and readable paths.</li>
      <li>Create combat spaces that support movement, cover usage, and clear enemy pressure.</li>
      <li>Use environmental storytelling to make the space feel grounded in the world of S.O.R.N.</li>
      <li>Build pacing through alternating exploration, tension, encounters, and payoff moments.</li>
    </ul>
  </div>

  <!-- MAPS -->
  <div class="section">
    <h2>Level Maps</h2>
    <p>
      Replace these with top-down maps, blockouts, or annotated screenshots showing
      player flow, encounter zones, and key points of interest.
    </p>

    <div class="image-grid">
      <img src="./sorn-map-01.png" class="image">
      <img src="./sorn-map-02.png" class="image">
    </div>
  </div>

  <!-- BEAT BREAKDOWN -->
  <div class="section">
    <h2>Beat Breakdown</h2>

    <div class="beat">
      <div class="beat-number">Beat 01</div>
      <h3>Opening Approach</h3>
      <p>
        <strong>Design Intent:</strong> Establish the mood of the level and introduce
        the player to the environment before combat escalates.
      </p>
      <ul>
        <li>Use lighting and composition to pull the player toward the critical path.</li>
        <li>Keep early enemy pressure controlled so the player can understand the space.</li>
        <li>Introduce visual landmarks that help the player build a mental map.</li>
      </ul>
      <img src="./sorn-beat-01.png" class="image">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 02</div>
      <h3>First Combat Space</h3>
      <p>
        <strong>Design Intent:</strong> Create a readable encounter that teaches the
        player how movement, cover, and enemy placement affect combat decisions.
      </p>
      <ul>
        <li>Place cover to break sightlines and support repositioning.</li>
        <li>Use enemy placement to encourage movement instead of passive play.</li>
        <li>Keep exits visible so the player always understands where progression continues.</li>
      </ul>
      <img src="./sorn-beat-02.png" class="image">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 03</div>
      <h3>Main Encounter</h3>
      <p>
        <strong>Design Intent:</strong> Deliver the level’s most intense combat space
        with stronger enemy pressure, verticality, or layered objectives.
      </p>
      <ul>
        <li>Use larger space to allow multiple combat approaches.</li>
        <li>Layer enemies to create pressure from different angles.</li>
        <li>Design the layout so aggressive and cautious players both have viable paths.</li>
      </ul>
      <img src="./sorn-beat-03.png" class="image">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 04</div>
      <h3>Final Payoff</h3>
      <p>
        <strong>Design Intent:</strong> End the level with a memorable moment that
        connects gameplay, environment, and story.
      </p>
      <ul>
        <li>Use a strong visual reveal or arena-style space to signal climax.</li>
        <li>Keep navigation simple so the player focuses on the encounter.</li>
        <li>Support cinematic pacing through composition and environmental framing.</li>
      </ul>
      <img src="./sorn-beat-04.png" class="image">
    </div>
  </div>

  <!-- GALLERY -->
  <div class="section">
    <h2>Image Gallery</h2>

    <div class="image-grid">
      <img src="./sorn-gallery-01.png" class="image">
      <img src="./sorn-gallery-02.png" class="image">
      <img src="./sorn-gallery-03.png" class="image">
      <img src="./sorn-gallery-04.png" class="image">
    </div>
  </div>

  <!-- PROCESS -->
  <div class="section">
    <h2>Process & Documentation</h2>

    <h3>Level Design Document</h3>
    <p>
      Before building the level, I planned the player route, encounter beats, narrative context,
      and intended pacing. This helped keep the level focused and gave each section a clear design purpose.
    </p>

    <ul>
      <li>Defined the level’s narrative purpose and player experience goals.</li>
      <li>Mapped critical path, encounter zones, and points of interest.</li>
      <li>Used documentation to keep design decisions aligned throughout production.</li>
    </ul>

    <a class="back" href="./sorn-ldd.pdf" target="_blank">View Level Design Document →</a>
  </div>

  <!-- LEARNINGS -->
  <div class="section">
    <h2>Conclusion & Learnings</h2>
    <p>
      This project strengthened my understanding of how level layout, encounter design,
      and cinematic pacing work together. The biggest challenge was balancing clarity with
      tension: the player needed to feel pressured, but never lost.
    </p>

    <h3>Knowledge Gained</h3>
    <ul>
      <li>Improved understanding of player routing and encounter pacing.</li>
      <li>Stronger use of landmarks, lighting, and spatial composition for guidance.</li>
      <li>More experience designing spaces around gameplay goals instead of only visuals.</li>
    </ul>

    <h3>Areas for Growth</h3>
    <ul>
      <li>Continue improving early blockout iteration before final art pass.</li>
      <li>Add more annotated before/after comparisons to explain design decisions visually.</li>
      <li>Refine scripted/cinematic moments to better support environmental storytelling.</li>
    </ul>
  </div>

  <a class="back" href="./index.html">← Back to Portfolio</a>

</div>
