---
layout: default
title: Devraj "Dev" Singh - Game Design Portfolio
---

<style>
html { scroll-behavior: smooth; }

  /* FOOTER */
.footer {
  margin-top: 60px;
  border-top: 1px solid #1f2937;
  padding: 20px 0;
}

.footer-inner {
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 24px;
  display: flex;
  justify-content: space-between;
  font-size: 13px;
  color: #7f8aa3;
}

body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: "Inter", sans-serif;
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
  font-size: 36px;
  margin-bottom: 6px;
  letter-spacing: -0.5px;
}

.hero p {
  font-size: 20px;
  color: #a1a8b5;
}

/* SECTION */
.section {
  margin-top: 30px;
}

.section-title {
  display: flex;
  align-items: center;
  gap: 18px;

  font-size: 22px;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: #eaeaea;

  margin-bottom: 28px;
}

/* long line */
.section-title::before {
  content: "";
  width: 120px;
  height: 1px;
  background: #3b82f6;
  opacity: 0.7;
}

.section-title::after {
  width: 60%;
  background: #3b82f6; /* subtle accent line */
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 36px;
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
  box-shadow: 0 8px 30px rgba(59, 130, 246, 0.15);
}

.card img,
.card iframe {
  width: 100%;
  height: 360px;
  display: block;
  object-fit: cover;
}

/* VIDEO HOVER */
.video-wrapper {
  position: relative;
  height: 360px;
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
.card-body {
  padding: 30px;
}

.card-body h3 {
  font-size: 42px;
  margin: 0 0 18px;
  letter-spacing: -1px;
  line-height: 1;
}

.card-body p {
  color: #b2bac7;
  font-size: 22px;
  line-height: 1.7;
  max-width: 800px;
}

.link {
  display: inline-block;
  margin-top: 28px;
  color: #60a5fa;
  text-decoration: none;
  font-size: 12px;
  letter-spacing: 4px;
  text-transform: uppercase;
  font-weight: 700;
  transition: 0.2s ease;
}

.link:hover {
  transform: translateX(6px);
}

.video-wrapper::after {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(
    to right,
    rgba(11,15,23,0.1),
    rgba(11,15,23,0.55)
  );
  pointer-events: none;
}

/* MOBILE */
@media (max-width: 768px) {
  .grid { grid-template-columns: 1fr; }

  .hero h1 {
    font-size: 26px;
  }
}
</style>

<div class="container">

  <!-- HERO (COMPACT) -->
  <div class="hero">
    <h1>Devraj "Dev" Singh</h1>
    <p>With a B.S. in Game Design, I am passionate about designing immersive gameplay experiences through level design, cinematic sequencing, gameplay systems, and player-focused interaction.</p>
  </div>

  <!-- PROJECTS -->
  <div class="section">
    <div class="section-title">Projects</div>

    <div class="grid">

<!-- S.O.R.N -->
<div class="card video-card">
  <div class="video-wrapper">

    <!-- THUMBNAIL (shows first) -->
    <img src="./sorn-thumb.png" class="thumbnail">

    <!-- VIDEO (appears on hover) -->
    <iframe class="video"
      src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID?autoplay=1&mute=1&controls=0&loop=1&playlist=YOUR_VIDEO_ID">
    </iframe>

  </div>

  <div class="card-body">
    <h3>S.O.R.N - The Lab</h3>
    <p>Level 2 - The mission is to uncover the truth about the superweapon, investigate and fight through a lab facility with new enemies and boss encounters.</p>
    <a class="link" href="./sorn.html"> Explore the Level →</a>
  </div>
</div>


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
          <a class="link" href="./abyssal-shade.html">Enter the Experience →</a>
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
  <!-- FOOTER -->
<div class="footer">
  <div class="footer-inner">
    <div>2026 Devraj Singh</div>
    <div>DS</div>
  </div>
</div>

</div>
