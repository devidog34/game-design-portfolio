---
layout: default
title: About - Dev Singh
---

<style>
body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

.container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 60px 24px 100px;
}

/* HERO */
.hero {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 40px;
  align-items: center;
  margin-bottom: 60px;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 10px;
}

.hero p {
  color: #9aa4b2;
  line-height: 1.6;
}

.profile-img {
  width: 100%;
  border-radius: 12px;
  border: 1px solid #1f2937;
}

/* SECTION CARDS */
.section {
  margin: 40px 0;
  padding: 24px;
  background: #111827;
  border: 1px solid #1f2937;
  border-radius: 10px;
}

.section h2 {
  font-size: 18px;
  margin-bottom: 10px;
}

.section p {
  color: #9aa4b2;
  line-height: 1.6;
}

/* CONTACT GRID */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin-top: 20px;
}

.contact-box {
  background: #0b0f17;
  border: 1px solid #1f2937;
  padding: 16px;
  border-radius: 8px;
  transition: 0.2s ease;
}

.contact-box:hover {
  border-color: #3b82f6;
}

.contact-box h4 {
  font-size: 12px;
  color: #7f8aa3;
  margin-bottom: 6px;
  text-transform: uppercase;
}

.contact-box a, .contact-box p {
  margin: 0;
  color: #eaeaea;
  text-decoration: none;
}

/* BUTTON */
.button {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 16px;
  border: 1px solid #3b82f6;
  border-radius: 6px;
  color: #60a5fa;
  text-decoration: none;
  transition: 0.2s ease;
}

.button:hover {
  background: #3b82f6;
  color: white;
}

/* BACK */
.back {
  display: inline-block;
  margin-top: 60px;
  color: #60a5fa;
  text-decoration: none;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero {
    grid-template-columns: 1fr;
  }

  .contact-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="container">

  <!-- HERO -->
  <div class="hero">

    <div>
      <h1>Devraj "Dev" Singh</h1>
      <p>
        Game Designer focused on gameplay systems, level design, and cinematic player experiences.
        I specialize in creating interactive moments that feel intentional, responsive, and immersive.
      </p>
    </div>

    <!-- REPLACE THIS IMAGE -->
    <img src="./profile.jpg" class="profile-img">
  </div>

  <!-- GOAL -->
  <div class="section">
    <h2>The Goal</h2>
    <p>
      My goal is to create immersive gameplay experiences that resonate with players through strong design, 
      responsive systems, and meaningful interaction. I aim to bridge technical implementation with creative direction 
      to build experiences that feel both polished and intentional.
    </p>
  </div>

  <!-- WHAT I DO -->
  <div class="section">
    <h2>What I Do</h2>
    <p>
      I design and implement gameplay systems that emphasize player feel, clarity, and interaction.
      My work focuses on:
    </p>
    <p>
      • Gameplay Systems & Mechanics<br>
      • Level Design & Player Flow<br>
      • Cinematic Gameplay & Sequencing<br>
      • Physics-Based Interaction Design
    </p>
  </div>

  <!-- CONTACT -->
  <div class="section">
    <h2>Contact</h2>
    <p>
      I’m open to opportunities in game design, level design, and cinematic gameplay.
      Feel free to reach out for collaboration or professional inquiries.
    </p>

    <div class="contact-grid">

      <div class="contact-box">
        <h4>Email</h4>
        <a href="mailto:devrajssingh@yahoo.com">devrajssingh@yahoo.com</a>
      </div>

      <div class="contact-box">
        <h4>Phone</h4>
        <p>904-827-3160</p>
      </div>

      <div class="contact-box">
        <h4>LinkedIn</h4>
        <a href="https://www.linkedin.com/in/devraj-singh-b62971261" target="_blank">
          View Profile
        </a>
      </div>

      <div class="contact-box">
        <h4>Itch.io</h4>
        <a href="https://devidog34.itch.io/" target="_blank">
          View Projects
        </a>
      </div>

    </div>
  </div>

  <!-- RESUME -->
  <div class="section">
    <h2>Resume</h2>
    <p>
      Download my resume for a full overview of my experience, skills, and projects.
    </p>

    <!-- ADD YOUR FILE -->
    <a class="button" href="./resume.pdf" target="_blank">View Resume</a>
  </div>

  <!-- BACK -->
  <a class="back" href="./index.html">← Back to Portfolio</a>

</div>
