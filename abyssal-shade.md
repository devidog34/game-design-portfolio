---
layout: default
title: Abyssal Shade - Dev Singh
---

<style>
body {
  background: #0b0f17;
  color: #eaeaea;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

.container {
  max-width: 900px;
  margin: 0 auto;
  padding: 40px 24px 80px;
}

.hero-video {
  width: 100%;
  height: 420px;
  border: none;
  margin-bottom: 30px;
}

h1 {
  font-size: 42px;
  margin-bottom: 10px;
}

.subtitle {
  color: #9aa4b2;
  margin-bottom: 30px;
}

.info-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin: 30px 0;
}

.info-box {
  background: #111827;
  border: 1px solid #1f2937;
  padding: 16px;
  border-radius: 8px;
}

.info-box h4 {
  font-size: 12px;
  color: #7f8aa3;
  margin-bottom: 6px;
  text-transform: uppercase;
}

.section {
  margin: 60px 0;
}

.section h2 {
  font-size: 22px;
  margin-bottom: 12px;
}

.section p {
  color: #9aa4b2;
  line-height: 1.6;
}

.image {
  width: 100%;
  margin-top: 20px;
  border-radius: 8px;
}

.back {
  display: inline-block;
  margin-top: 60px;
  color: #60a5fa;
  text-decoration: none;
}
</style>

<div class="container">

  <!-- HERO VIDEO -->
  <iframe class="hero-video"
    src="https://www.youtube-nocookie.com/embed/-GJStUShhT0?start=53&autoplay=1&mute=1&loop=1&playlist=-GJStUShhT0"
    allow="autoplay; encrypted-media"
    allowfullscreen>
  </iframe>

  <h1>Abyssal Shade</h1>
  <p class="subtitle">
    A physics-driven underwater gameplay system focused on fluid movement, environmental interaction, and emergent behavior.
  </p>

  <!-- INFO -->
  <div class="info-grid">
    <div class="info-box">
      <h4>Role</h4>
      <p>Gameplay Designer & Programmer</p>
    </div>

    <div class="info-box">
      <h4>Tools</h4>
      <p>Unity, C#, Physics System</p>
    </div>

    <div class="info-box">
      <h4>Focus</h4>
      <p>Movement Systems, AI Behavior, Environmental Design</p>
    </div>
  </div>

  <!-- OVERVIEW -->
  <div class="section">
    <h2>Overview</h2>
    <p>
      Abyssal Shade is an underwater gameplay prototype centered around controlling a manta ray navigating a dynamic ocean environment. 
      The core goal of the project was to create movement that feels fluid, responsive, and physically grounded while interacting with 
      environmental forces such as currents and nearby entities.
    </p>
  </div>

  <!-- DESIGN CHALLENGE -->
  <div class="section">
    <h2>Design Challenge</h2>
    <p>
      Traditional character controllers often feel rigid and disconnected when applied to underwater movement. 
      The challenge was to design a system that preserved player control while still feeling influenced by physics and environment.
    </p>
    <p>
      Additionally, creating believable schooling behavior for nearby fish required balancing performance with emergent motion that 
      feels natural rather than scripted.
    </p>
  </div>

  <!-- SOLUTION -->
  <div class="section">
    <h2>Solution</h2>
    <p>
      I implemented a physics-based movement system using force-driven controls rather than direct position manipulation. 
      This allowed the manta ray to accelerate, glide, and respond to environmental forces in a more organic way.
    </p>
    <p>
      Environmental currents were designed as directional force zones that dynamically influence movement, encouraging players 
      to navigate with awareness of their surroundings rather than relying solely on direct input.
    </p>
    <p>
      For AI behavior, I developed a schooling system where fish follow simple steering rules (alignment, cohesion, separation) 
      to produce emergent group motion. This allowed large groups to behave believably without heavy scripting.
    </p>
  </div>

  <!-- OUTCOME -->
  <div class="section">
    <h2>Outcome</h2>
    <p>
      The resulting system created a strong sense of flow and immersion, with movement that feels both player-driven and environmentally influenced.
    </p>
    <p>
      The project successfully demonstrates:
    </p>
    <p>
      • Physics-based player control design<br>
      • Emergent AI behavior systems<br>
      • Environmental interaction as a core gameplay mechanic
    </p>
    <p>
      If expanded further, I would refine player feedback systems (camera, VFX, audio) to enhance clarity and responsiveness.
    </p>
  </div>

  <!-- IMAGE -->
  <img src="./manta.gif" class="image">

  <!-- BACK -->
  <a class="back" href="./index.html">← Back to Portfolio</a>

</div>
