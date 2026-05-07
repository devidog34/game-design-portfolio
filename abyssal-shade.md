---
layout: default
title: Abyssal Shade - Dev Singh
---

<style>
.pdf-viewer-box {
  margin-top: 24px;
}

.pdf-viewer {
  width: 100%;
  height: 650px;
  border: 1px solid #1f2937;
  border-radius: 10px;
  background: #111827;
}

.doc-button {
  display: inline-block;
  margin-top: 18px;
  padding: 14px 20px;
  background: #111827;
  border: 1px solid #1f2937;
  border-radius: 8px;
  color: #eaeaea;
  text-decoration: none;
  font-weight: 600;
  letter-spacing: 1px;
  transition: 0.2s ease;
}

.doc-button:hover {
  border-color: #3b82f6;
  transform: translateY(-2px);
  color: #ffffff;
}

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
  color: #3b82f6;
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
    <a href="./index.html">Projects</a> / Abyssal Shade
  </div>

  <div class="hero">
    <div class="kicker">Unity · Level Designer · 3rd Person Adventure</div>
    <h1>Abyssal Shade</h1>
    <p>
      A relaxing underwater exploration experience focused on player freedom, verticality,
      and distinct environmental spaces that support omni-directional movement.
    </p>
  </div>

  <!-- MAIN VIDEO -->
  <div class="section">
    <h2>Gameplay Showcase</h2>
<iframe class="video"
  src="https://www.youtube-nocookie.com/embed/-GJStUShhT0?start=53&autoplay=1&mute=1&controls=0&loop=1&playlist=-GJStUShhT0&playsinline=1"
  allow="autoplay; encrypted-media"
  allowfullscreen>
</iframe>
  </div>

  <!-- OVERVIEW -->
  <div class="section">
    <h2>Project Overview</h2>
    <p>
      Abyssal Shade was designed around giving players a single open underwater environment to explore.
      As level designer, my priority was to create a map that felt open and free while still giving the player
      recognizable landmarks, readable spaces, and clear areas of interest.
    </p>

    <div class="callout-grid">
      <div class="callout">
        <h4>Role</h4>
        <p>Level Designer</p>
      </div>

      <div class="callout">
        <h4>Engine</h4>
        <p>Unity</p>
      </div>

      <div class="callout">
        <h4>Focus</h4>
        <p>Open Layout, Verticality, Environmental Readability</p>
      </div>
    </div>
  </div>

  <!-- LEVEL GOALS -->
  <div class="section">
    <h2>Level Goals</h2>
    <ul>
      <li>Create a relaxing and serene underwater exploration space.</li>
      <li>Make each area visually distinct so players can recognize where they are from anywhere in the map.</li>
      <li>Use verticality to complement the game’s omni-directional manta ray movement.</li>
      <li>Balance player freedom with subtle environmental guidance.</li>
      <li>Hide the main level area during the tutorial cave to create a stronger reveal moment.</li>
    </ul>
  </div>

  <!-- MAPS / LAYOUT -->
  <div class="section">
    <h2>Level Layout</h2>
    <p>
      The layout went through early test scenes and temporary environments before landing on the final structure.
      The goal was to understand where the player should naturally want to go, while still letting them choose
      the order in which they explored and revived each area of the map.
    </p>

    <div class="image-grid">
      <img src="{{ '/abyssal-map-01.png' | relative_url }}" class="image" alt="Abyssal Shade early map layout">
      <img src="{{ '/abyssal-map-02.png' | relative_url }}" class="image" alt="Abyssal Shade final map layout">
    </div>
  </div>

  <!-- BEAT BREAKDOWN -->
  <div class="section">
    <h2>Design Breakdown</h2>

    <div class="beat">
      <div class="beat-number">Beat 01</div>
      <h3>Tutorial Cave</h3>
      <p>
        <strong>Design Intent:</strong> Introduce the player to movement and atmosphere in a controlled space
        before revealing the larger underwater environment.
      </p>
      <ul>
        <li>Used a tighter cave layout to teach movement without overwhelming the player.</li>
        <li>Set dressed the area heavily with rocks and seaweed to build mood.</li>
        <li>Kept the main level hidden to make the exit reveal feel more impactful.</li>
      </ul>
      <img src="{{ '/abyssal-beat-01.png' | relative_url }}" class="image" alt="Abyssal Shade tutorial cave">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 02</div>
      <h3>Open World Reveal</h3>
      <p>
        <strong>Design Intent:</strong> Transition the player from a guided tutorial space into a larger environment
        that invites curiosity and exploration.
      </p>
      <ul>
        <li>Framed the exit of the cave to reveal the larger playable space.</li>
        <li>Used landmarks and color contrast to distinguish areas from a distance.</li>
        <li>Allowed the player to choose where to go next instead of forcing a single route.</li>
      </ul>
      <img src="{{ '/abyssal-beat-02.png' | relative_url }}" class="image" alt="Abyssal Shade open world reveal">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 03</div>
      <h3>Distinct Level Areas</h3>
      <p>
        <strong>Design Intent:</strong> Create multiple recognizable sections that support exploration without
        making the player feel lost.
      </p>
      <ul>
        <li>Designed 3–4 major areas with unique points of interest.</li>
        <li>Placed areas at different elevations to reinforce vertical exploration.</li>
        <li>Used environmental identity to help players orient themselves naturally.</li>
      </ul>
      <img src="{{ '/abyssal-beat-03.png' | relative_url }}" class="image" alt="Abyssal Shade distinct areas">
    </div>

    <div class="beat">
      <div class="beat-number">Beat 04</div>
      <h3>Kitbashing & Set Dressing</h3>
      <p>
        <strong>Design Intent:</strong> Build believable underwater spaces using available assets while maintaining
        strong composition and readability.
      </p>
      <ul>
        <li>Set dressed 3/4 of the level using kitbashed artist assets.</li>
        <li>Hand-placed rock assets to blend forms and create natural silhouettes.</li>
        <li>Rotated and layered assets to avoid repetition and support visual flow.</li>
      </ul>
      <img src="{{ '/abyssal-beat-04.png' | relative_url }}" class="image" alt="Abyssal Shade set dressing">
    </div>
  </div>

  <!-- GALLERY -->
  <div class="section">
    <h2>Image Gallery</h2>

    <div class="image-grid">
      <img src="{{ '/abyssal-gallery-01.png' | relative_url }}" class="image" alt="Abyssal Shade gallery image 1">
      <img src="{{ '/abyssal-gallery-02.png' | relative_url }}" class="image" alt="Abyssal Shade gallery image 2">
      <img src="{{ '/abyssal-gallery-03.png' | relative_url }}" class="image" alt="Abyssal Shade gallery image 3">
      <img src="{{ '/abyssal-gallery-04.png' | relative_url }}" class="image" alt="Abyssal Shade gallery image 4">
    </div>
  </div>

  <!-- PROCESS -->
  <div class="section">
    <h2>Process & Documentation</h2>

    <h3>Level Design Process</h3>
    <p>
      In a short production cycle, the level design process focused on quick iteration: testing spaces,
      blocking out routes, defining major points of interest, and refining the environment through kitbashing.
      The design needed to support a relaxing tone while still encouraging players to explore every area.
    </p>

    <ul>
      <li>Designed the level map layout.</li>
      <li>Set dressed major level areas through kitbashing.</li>
      <li>Prioritized verticality and freedom of movement.</li>
      <li>Balanced open exploration with recognizable landmarks and area identity.</li>
    </ul>

    <a
      href="{{ '/abyssal-design-doc.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      class="doc-button">
      Open Full Design Document →
    </a>
  </div>

  <!-- LEARNINGS -->
  <div class="section">
    <h2>Conclusion & Learnings</h2>
    <p>
      Abyssal Shade strengthened my understanding of how open environments can support player freedom
      without sacrificing readability. The biggest challenge was making the map feel open while still giving
      the player enough visual information to understand where they were and where they might want to go next.
    </p>

    <h3>Knowledge Gained</h3>
    <ul>
      <li>Improved understanding of open-world layout readability.</li>
      <li>Stronger use of verticality as a level design tool.</li>
      <li>More experience using kitbashing and set dressing to create distinct spaces.</li>
      <li>Better understanding of how reveal moments affect player motivation.</li>
    </ul>

    <h3>Areas for Growth</h3>
    <ul>
      <li>Add more annotated maps showing player routes and area identity.</li>
      <li>Improve environmental signposting through lighting, silhouettes, and color contrast.</li>
      <li>Continue refining the balance between open exploration and guided pathing.</li>
    </ul>
  </div>

  <a class="back" href="./index.html">← Back to Projects Page</a>

</div>
