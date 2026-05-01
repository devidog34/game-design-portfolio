---
layout: default
title: Dev Singh - Game Design Portfolio
---

<div class="container">

  <div class="topbar">
    <div class="brand">
      <img src="./dev-logo.jpg" alt="Dev With Dev Logo" />
      <span>Dev With Dev</span>
    </div>
  </div>

<style>
/* =========================
   AAA STYLE SYSTEM
========================= */

.topbar {
  position: sticky;
  top: 0;
  width: 100%;
  padding: 18px 0;
  background: rgba(11, 15, 23, 0.85);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #1f2937;
  z-index: 999;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 24px;
}

.brand img {
  width: 34px;
  height: 34px;
  object-fit: contain;
}

.brand span {
  font-size: 16px;
  font-weight: 600;
  letter-spacing: 0.5px;
  color: #eaeaea;
}

body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

.container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 24px;
}

.hero {
  padding: 110px 0 70px;
  text-align: center;
}

.hero h1 {
  font-size: 54px;
  letter-spacing: -1px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 18px;
  color: #a9b0bb;
  max-width: 600px;
  margin: 0 auto;
}

.nav {
  margin-top: 18px;
}

.nav a {
  margin: 0 12px;
  color: #ffffff;
  text-decoration: none;
  font-weight: 500;
  opacity: 0.75;
}

.nav a:hover {
  opacity: 1;
}

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

.grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 26px;
}

.card {
  background: #111827;
  border: 1px solid #1f2937;
  border-radius: 10px;
  overflow: hidden;
  transition: transform 0.25s ease, border 0.25s ease;
}

.card:hover {
  transform: translateY(-6px);
  border-color: #3b82f6;
}

.card img {
  width: 100%;
  display: block;
}

.card-body {
  padding: 16px;
}

.card h3 {
  margin: 0 0 8px;
  font-size: 18px;
}

.card p {
  margin: 0;
  color: #9aa4b2;
  font-size: 14px;
  line-height: 1.5;
}

.link {
  display: inline-block;
  margin-top: 12px;
  color: #60a5fa;
  text-decoration: none;
  font-weight: 500;
}

.link:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
  }

  .hero h1 {
    font-size: 38px;
  }
}
</style>

  <!-- HERO -->
  <div class="hero">
    <h1>Dev Singh</h1>
    <p>Game Designer focused on systems, gameplay mechanics, and immersive interaction design.</p>

    <div class="nav">
      <a href="mailto:devrajssingh@yahoo.com">Email</a>
      <a href="https://www.linkedin.com/in/devraj-singh-b62971261" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a href="https://devidog34.itch.io/" target="_blank" rel="noopener noreferrer">Itch.io</a>
    </div>
  </div>

  <!-- PROJECTS -->
  <div class="section">
    <div class="section-title">Featured Projects</div>

    <div class="grid">

      <div class="card">
        <img src="./manta.gif">
        <div class="card-body">
          <h3>🐠 Manta Ray</h3>
          <p>Physics-based underwater movement system with AI schooling behavior and dynamic current forces.</p>
          <a class="link" href="./manta-ray.html">View Case Study →</a>
        </div>
      </div>

      <div class="card">
        <img src="./unreal.gif">
        <div class="card-body">
          <h3>⚔️ Combat Prototype</h3>
          <p>Third-person combat system focused on feedback, responsiveness, and cinematic event sequencing.</p>
          <a class="link" href="./combat-prototype.html">View Case Study →</a>
        </div>
      </div>

      <div class="card">
        <img src="./level.gif">
        <div class="card-body">
          <h3>🧱 Level Design</h3>
          <p>Level design experiments focused on player flow, spatial storytelling, and pacing control.</p>
          <a class="link" href="./level-design.html">View Case Study →</a>
        </div>
      </div>

    </div>
  </div>

  <!-- ABOUT -->
  <div class="section">
    <div class="section-title">About</div>
    <p style="max-width:700px; color:#9aa4b2; line-height:1.7;">
      I design gameplay systems that focus on player feel, interaction clarity, and environmental storytelling.
      My work emphasizes physics-based mechanics, AI behavior systems, and cinematic gameplay pacing.
    </p>
  </div>

</div>
