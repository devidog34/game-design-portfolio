---
layout: default
title: Level Design - Dev Singh
---

<style>
.container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 40px 24px 80px;
}

/* HERO */
.hero {
  margin-bottom: 40px;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 8px;
}

.hero p {
  color: #9aa4b2;
  max-width: 600px;
}

/* SECTION */
.section {
  margin: 50px 0;
}

.section h2 {
  font-size: 18px;
  margin-bottom: 12px;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 26px;
}

/* CARD */
.card {
  background: #111827;
  border: 1px solid #1f2937;
  border-radius: 10px;
  overflow: hidden;
  transition: 0.25s ease;
}

.card:hover {
  transform: translateY(-6px);
  border-color: #3b82f6;
}

.card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.card-body {
  padding: 16px;
}

.card h3 {
  margin-bottom: 6px;
}

.card p {
  color: #9aa4b2;
  font-size: 14px;
}

.link {
  display: inline-block;
  margin-top: 8px;
  color: #60a5fa;
  text-decoration: none;
}

/* IMAGE STRIP */
.full-image {
  width: 100%;
  border-radius: 10px;
  margin-top: 20px;
}
</style>

<div class="container">

  <!-- HERO -->
  <div class="hero">
    <h1>Level Design</h1>
    <p>
      I design levels that guide player movement, communicate intent through environment,
      and create pacing through spatial layout and interaction.
    </p>
  </div>

  <!-- DESIGN APPROACH -->
  <div class="section">
    <h2>Design Approach</h2>
    <p style="color:#9aa4b2;">
      My level design process focuses on player flow, readability, and environmental storytelling.
      I use layout, lighting, and composition to guide players naturally without relying on UI.
    </p>
  </div>

  <!-- PROJECTS -->
  <div class="section">
    <h2>Selected Work</h2>

    <div class="grid">

      <!-- PROJECT 1 -->
      <div class="card">
        <img src="./lone-town.gif">
        <div class="card-body">
          <h3>The Lone Town</h3>
          <p>Atmospheric exploration space focused on player navigation and mood.</p>
          <a class="link" href="./lone-town.html">View Project →</a>
        </div>
      </div>

      <!-- PROJECT 2 -->
      <div class="card">
        <img src="./david.gif">
        <div class="card-body">
          <h3>David’s Mighty Men</h3>
          <p>Level design focused on player positioning and encounter flow.</p>
          <a class="link" href="./davids-mighty-men.html">View Project →</a>
        </div>
      </div>

    </div>
  </div>

  <!-- VISUAL EXAMPLES -->
  <div class="section">
    <h2>Layout & Flow Examples</h2>

    <p style="color:#9aa4b2;">
      Examples of blockouts and final layouts showing player guidance and spatial composition.
    </p>

    <!-- REPLACE THESE -->
    <img src="./level1.png" class="full-image">
    <img src="./level2.png" class="full-image">
  </div>

</div>
