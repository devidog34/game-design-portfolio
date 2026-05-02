---
layout: default
title: Devraj "Dev" Singh - Game Design Portfolio
---

<style>
/* =========================
   AAA STYLE SYSTEM
========================= */

html {
  scroll-behavior: smooth;
}

body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

/* CONTAINER */
.container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 24px;
}

/* ===== TOPBAR ===== */
.topbar {
  position: sticky;
  top: 0;
  width: 100%;
  background: rgba(11, 15, 23, 0.85);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #1f2937;
  z-index: 999;
}

.topbar-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 16px 24px;
  max-width: 1040px;
  margin: 0 auto;
}

.brand {
  display: flex;
  align-items: center;
  gap: 10px;
}

.brand img {
  width: 32px;
  height: 32px;
}

.brand span {
  font-weight: 600;
  font-size: 15px;
}

/* RIGHT SIDE */
.topbar-right {
  display: flex;
  align-items: center;
  gap: 30px;
}

/* CONTACT */
.contact a {
  margin: 0 6px;
  font-size: 14px;
  color: #9aa4b2;
  text-decoration: none;
}

.contact a:hover {
  color: #ffffff;
}

/* NAV */
.nav a {
  margin-left: 18px;
  font-size: 14px;
  text-decoration: none;
  color: #ffffff;
  font-weight: 500;
  opacity: 0.8;
}

.nav a:hover {
  opacity: 1;
}

/* HERO */
.hero {
  padding: 110px 0 70px;
  text-align: center;
}

.hero h1 {
  font-size: 54px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  color: #a9b0bb;
  max-width: 600px;
  margin: 0 auto;
}

/* SECTIONS */
.section {
  margin: 90px 0;
}

.section-title {
  font-size: 22px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #7f8aa3;
  margin-bottom: 24px;
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

/* IMAGE + VIDEO SIZE */
.card img,
.card iframe {
  width: 100%;
  height: 200px;
  display: block;
  border: none;
}

/* ===== VIDEO HOVER SYSTEM ===== */
.video-wrapper {
  position: relative;
  width: 100%;
  height: 200px;
  overflow: hidden;
}

.thumbnail {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: opacity 0.3s ease;
}

.video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.3s ease;
}

.video-card:hover .video {
  opacity: 1;
}

.video-card:hover .thumbnail {
  opacity: 0;
}

/* CONTENT */
.card-body {
  padding: 16px;
}

.card h3 {
  margin-bottom: 8px;
}

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

.link:hover {
  text-decoration: underline;
}

/* MOBILE */
@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
  }

  .topbar-inner {
    flex-direction: column;
    gap: 10px;
  }

  .topbar-right {
    flex-direction: column;
    gap: 10px;
  }

  .hero h1 {
    font-size: 38px;
  }
}
</style>

<!-- ===== TOPBAR ===== -->
<div class="topbar">
  <div class="topbar-inner">

   <a href="./index.html" class="brand">
     <img src="./dev-logo.jpg" alt="Dev With Dev Logo">
     <span>Dev With Dev</span>
   </a>

    <div class="topbar-right">

      <div class="contact">
        <a href="mailto:devrajssingh@yahoo.com">Email</a>
        <a href="https://www.linkedin.com/in/devraj-singh-b62971261" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        <a href="https://devidog34.itch.io/" target="_blank" rel="noopener noreferrer">Itch.io</a>
      </div>

      <div class="nav">
        <a href="#level-design">Level Design</a>
        <a href="#cinematic-design">Cinematic Design</a>
      </div>

    </div>

  </div>
</div>

<div class="container">

  <!-- HERO -->
  <div class="hero">
    <h1>Devraj "Dev" Singh</h1>
    <p>Game Designer focused on systems, level design, and cinematic gameplay experiences.</p>
  </div>

  <!-- LEVEL DESIGN -->
  <div id="level-design" class="section">
    <div class="section-title">Level Design</div>

    <div class="grid">
      <div class="card">
        <img src="./level.gif">
        <div class="card-body">
          <h3>Level Design Experiments</h3>
          <p>Player flow, spatial storytelling, and environment-driven pacing.</p>
          <a class="link" href="./level-design.html">View Case Study →</a>
        </div>
      </div>
    </div>
  </div>

  <!-- CINEMATIC DESIGN -->
  <div id="cinematic-design" class="section">
    <div class="section-title">Cinematic Design</div>

    <div class="grid">

      <!-- MANTA VIDEO CARD -->
      <div class="card video-card">
        <div class="video-wrapper">

          <img src="./manta-thumb.jpg" class="thumbnail">

          <iframe 
            class="video"
            src="https://www.youtube-nocookie.com/embed/-GJStUShhT0?start=53&autoplay=1&mute=1&controls=0&playsinline=1&loop=1&playlist=-GJStUShhT0&modestbranding=1"
            allow="autoplay; encrypted-media">
          </iframe>

        </div>

        <div class="card-body">
          <h3>Manta Ray</h3>
          <p>Environmental interaction and movement-driven cinematic gameplay.</p>
          <a class="link" href="./manta-ray.html">View Case Study →</a>
        </div>
      </div>

      <!-- COMBAT -->
      <div class="card">
        <img src="./unreal.gif">
        <div class="card-body">
          <h3>Combat Prototype</h3>
          <p>Cinematic combat flow, sequencing, and player feedback systems.</p>
          <a class="link" href="./combat-prototype.html">View Case Study →</a>
        </div>
      </div>

    </div>
  </div>

</div>
