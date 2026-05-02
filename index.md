---
layout: default
title: Devraj "Dev" Singh - Game Design Portfolio
---

<style>
html { scroll-behavior: smooth; }

body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

/* CONTAINER */
.container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 20px 24px 40px;
}

/* ===== TOPBAR ===== */
.topbar {
  position: sticky;
  top: 0;
  width: 100%;
  background: rgba(11, 15, 23, 0.9);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #1f2937;
  z-index: 999;
}

.topbar-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1040px;
  margin: 0 auto;
  padding: 14px 24px;
}

/* LEFT */
.brand {
  display: flex;
  align-items: center;
  gap: 10px;
  text-decoration: none;
  color: inherit;
}

.brand img {
  width: 32px;
  height: 32px;
}

/* RIGHT */
.topbar-right {
  display: flex;
  align-items: center;
  gap: 30px;
}

.contact a {
  margin: 0 6px;
  font-size: 13px;
  color: #9aa4b2;
  text-decoration: none;
}

.contact a:hover { color: #ffffff; }

.nav a {
  margin-left: 16px;
  font-size: 13px;
  color: #ffffff;
  text-decoration: none;
  opacity: 0.8;
}

.nav a:hover { opacity: 1; }

/* ===== HERO (SMALL + TIGHT) ===== */
.hero {
  padding: 40px 0 20px;
  text-align: center;
}

.hero h1 {
  font-size: 34px;
  margin-bottom: 6px;
}

.hero p {
  font-size: 15px;
  color: #9aa4b2;
  margin: 0;
}

/* SECTION */
.section {
  margin-top: 30px;
}

.section-title {
  font-size: 18px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #7f8aa3;
  margin-bottom: 16px;
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

.card img,
.card iframe {
  width: 100%;
  height: 200px;
  display: block;
}

/* VIDEO HOVER */
.video-wrapper {
  position: relative;
  height: 200px;
}

.thumbnail {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: opacity 0.3s ease;
}

.video {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.video-card:hover .video { opacity: 1; }
.video-card:hover .thumbnail { opacity: 0; }

/* CONTENT */
.card-body { padding: 16px; }

.card p {
  color: #9aa4b2;
  font-size: 14px;
}

.link {
  display: inline-block;
  margin-top: 10px;
  color: #60a5fa;
  text-decoration: none;
}

/* MOBILE */
@media (max-width: 768px) {
  .grid { grid-template-columns: 1fr; }

  .hero h1 {
    font-size: 26px;
  }
}
</style>

<!-- HEADER -->
<div class="topbar">
  <div class="topbar-inner">

    <a href="./index.html" class="brand">
      <img src="./dev-logo.jpg">
      <span>Dev With Dev</span>
    </a>

    <div class="topbar-right">

      <div class="contact">
        <a href="mailto:devrajssingh@yahoo.com">Email</a>
        <a href="https://www.linkedin.com/in/devraj-singh-b62971261" target="_blank">LinkedIn</a>
        <a href="https://devidog34.itch.io/" target="_blank">Itch.io</a>
      </div>

      <div class="nav">
        <a href="./level-design.html">Level Design</a>
        <a href="./cinematic-design.html">Cinematic</a>
      </div>

    </div>

  </div>
</div>

<div class="container">

  <!-- HERO (COMPACT) -->
  <div class="hero">
    <h1>Devraj "Dev" Singh</h1>
    <p>Game Designer focused on gameplay systems, player feel, and immersive interaction.</p>
  </div>

  <!-- PROJECTS -->
  <div class="section">
    <div class="section-title">Projects</div>

    <div class="grid">

      <!-- Abyssal Shade -->
      <div class="card video-card">
        <div class="video-wrapper">
          <img src="./manta-thumb.png" class="thumbnail">
          <iframe class="video"
            src="https://www.youtube-nocookie.com/embed/-GJStUShhT0?start=53&autoplay=1&mute=1&controls=0&loop=1&playlist=-GJStUShhT0">
          </iframe>
        </div>
        <div class="card-body">
          <h3>Abyssal Shade</h3>
          <p>Underwater gameplay system with environmental interaction.</p>
          <a class="link" href="./abyssal-shade.html">View Game →</a>
        </div>
      </div>

     <!-- The Lone Town -->
      <div class="card">
        <img src="./lone-town.gif">
        <div class="card-body">
          <h3>The Lone Town</h3>
          <p>Atmospheric environment focused on exploration and mood.</p>
          <a class="link" href="#">View Game →</a>
        </div>
      </div>

      <!-- S.O.R.N -->
      <div class="card">
        <img src="./sorn.gif">
        <div class="card-body">
          <h3>S.O.R.N</h3>
          <p>Experimental gameplay systems and combat interactions.</p>
          <a class="link" href="#">View Game →</a>
        </div>
      </div>

      <!-- Ripple Rescue -->
      <div class="card">
        <img src="./ripple.gif">
        <div class="card-body">
          <h3>Ripple Rescue</h3>
          <p>Mechanic-driven gameplay focused on player movement.</p>
          <a class="link" href="#">View Game →</a>
        </div>
      </div>

      <!-- David’s Mighty Men -->
      <div class="card">
        <img src="./david.gif">
        <div class="card-body">
          <h3>David’s Mighty Men</h3>
          <p>Team-based gameplay and character interaction systems.</p>
          <a class="link" href="#">View Game →</a>
        </div>
      </div>

    </div>

  </div>

</div>
