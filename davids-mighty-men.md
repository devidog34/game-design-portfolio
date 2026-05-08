---
layout: default
title: David's Mighty Men - Dev Singh
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
  color: #f4b860;
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
    <a href="./index.html">Projects</a> / David's Mighty Men
  </div>

  <div class="hero">
    <div class="kicker">Unreal Engine 5.6 · Hack N' Slash · Lead Designer</div>
    <h1>David's Mighty Men</h1>
    <p>
      A third-person hack-and-slash project focused on city level design, cinematic gameplay,
      enemy AI systems, level streaming, and fast-paced action sequencing.
    </p>
  </div>

  <!-- MAIN VIDEO -->
  <div class="section">
    <h2>Gameplay Showcase</h2>
    <iframe class="video"
      src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID?autoplay=0&controls=1"
      allowfullscreen>
    </iframe>
  </div>

  <!-- OVERVIEW -->
  <div class="section">
    <h2>Project Overview</h2>
    <p>
      David's Mighty Men is a third-person hack-and-slash project developed in Unreal Engine 5.6.
      As a developer on the project from conception, I worked across level design, cinematic design,
      gameplay implementation, and AI systems.
    </p>

    <p>
      My work included map layout sketches, blockouts, set dressing, kitbashing, level sequencing,
      camera blending, level streaming, and enemy AI implementation. The goal was to create a visually
      interesting city space that supported navigation, combat pacing, cinematic moments, and player flow.
    </p>

    <div class="callout-grid">
      <div class="callout">
        <h4>Role</h4>
        <p>Lead Designer / Lead Programmer</p>
      </div>

      <div class="callout">
        <h4>Engine</h4>
        <p>Unreal Engine 5.6</p>
      </div>

      <div class="callout">
        <h4>Focus</h4>
        <p>Level Design, Cinematics, AI Systems</p>
      </div>
    </div>
  </div>

  <!-- DESIGN GOALS -->
  <div class="section">
    <h2>Design Goals</h2>
    <ul>
      <li>Create a city layout that felt visually interesting, readable, and navigable.</li>
      <li>Use blockouts to test building placement, player routing, and points of interest.</li>
      <li>Support fast-paced hack-and-slash gameplay through encounter spacing and pathing.</li>
      <li>Use cinematic sequencing to establish the tone of gameplay.</li>
      <li>Implement enemy AI systems that created believable combat pressure.</li>
      <li>Optimize the project through level streaming and organized level structure.</li>
    </ul>
  </div>

  <!-- LEVEL MAPPING -->
  <div class="section">
    <h2>Level Mapping</h2>
    <p>
      The level began with map layout sketches and planning. The challenge was to create a map that stayed
      to scale while still feeling visually interesting and easy to navigate. The city needed recognizable
      routes, areas of interest, and believable pathways.
    </p>

    <div class="image-grid">
      <img src="{{ '/dmm-map-01.png' | relative_url }}" class="image" alt="David's Mighty Men level map sketch">
      <img src="{{ '/dmm-map-02.png' | relative_url }}" class="image" alt="David's Mighty Men city layout map">
    </div>
  </div>

  <!-- BREAKDOWN -->
  <div class="section">
    <h2>Design Breakdown</h2>

    <div class="beat">
      <div class="beat-number">Focus 01</div>
      <h3>Map Layout & Scale</h3>
      <p>
        <strong>Design Intent:</strong> Build a city layout that felt natural while keeping the player oriented
        and encouraging movement through important areas.
      </p>
      <ul>
        <li>Created map layout sketches to plan the city before engine implementation.</li>
        <li>Focused on scale, navigation, and visually interesting routes.</li>
        <li>Used city structure to support combat flow and cinematic framing.</li>
      </ul>
      <img src="{{ '/dmm-beat-01.png' | relative_url }}" class="image" alt="David's Mighty Men map layout">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 02</div>
      <h3>Blockouts & Player Pathing</h3>
      <p>
        <strong>Design Intent:</strong> Use blockouts to test building placement, sightlines, and player curiosity
        before committing to final art and set dressing.
      </p>
      <ul>
        <li>Fine-tuned building layout and player pathing through blockout passes.</li>
        <li>Used vertical buildings to create line-of-sight goals and navigation references.</li>
        <li>Placed openings and alleyways to pull player curiosity through the city.</li>
        <li>Compared layouts to identify which spaces felt natural and which needed revision.</li>
      </ul>
      <img src="{{ '/dmm-beat-02.png' | relative_url }}" class="image" alt="David's Mighty Men blockout">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 03</div>
      <h3>Set Dressing & Kitbashing</h3>
      <p>
        <strong>Design Intent:</strong> Use artist-created assets to shape the level into a believable city while
        still maintaining clear player routes and strong readability.
      </p>
      <ul>
        <li>Set dressed roughly 3/4 of the level through kitbashing.</li>
        <li>Fine-tuned line of sight, shadows, and environmental composition.</li>
        <li>Created navigable pathways so players could successfully move through the city.</li>
        <li>Populated the city with props, torches, enemies, and gameplay elements.</li>
      </ul>
      <img src="{{ '/dmm-beat-03.png' | relative_url }}" class="image" alt="David's Mighty Men set dressing">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 04</div>
      <h3>Level Sequences & Cinematics</h3>
      <p>
        <strong>Design Intent:</strong> Establish gameplay tone through fast-paced, energetic cinematics that
        transition smoothly back into player control.
      </p>
      <ul>
        <li>Designed and implemented in-game cinematics using Unreal Level Sequencer.</li>
        <li>Used camera blending, timing, and blocking to transition smoothly between cinematic cameras and gameplay cameras.</li>
        <li>Animated characters per cutscene to support narrative and action beats.</li>
        <li>Designed cinematic moments to support the pacing and tone of hack-and-slash gameplay.</li>
      </ul>
      <img src="{{ '/dmm-beat-04.png' | relative_url }}" class="image" alt="David's Mighty Men cinematic sequence">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 05</div>
      <h3>Enemy AI Systems</h3>
      <p>
        <strong>Design Intent:</strong> Create enemy combat behavior that could pressure the player through AI
        perception, behavior trees, and environmental queries.
      </p>
      <ul>
        <li>Implemented enemy AI systems using Behavior Trees and Sub-Trees.</li>
        <li>Used AI Perception to detect and react to the player.</li>
        <li>Used EQS systems to support enemy decision-making and positioning.</li>
        <li>Connected AI behavior to the overall combat and encounter pacing.</li>
      </ul>
      <img src="{{ '/dmm-beat-05.png' | relative_url }}" class="image" alt="David's Mighty Men AI systems">
    </div>
  </div>

  <!-- GALLERY -->
  <div class="section">
    <h2>Image Gallery</h2>

    <div class="image-grid">
      <img src="{{ '/dmm-gallery-01.png' | relative_url }}" class="image" alt="David's Mighty Men gallery image 1">
      <img src="{{ '/dmm-gallery-02.png' | relative_url }}" class="image" alt="David's Mighty Men gallery image 2">
      <img src="{{ '/dmm-gallery-03.png' | relative_url }}" class="image" alt="David's Mighty Men gallery image 3">
      <img src="{{ '/dmm-gallery-04.png' | relative_url }}" class="image" alt="David's Mighty Men gallery image 4">
    </div>
  </div>

  <!-- PROCESS -->
  <div class="section">
    <h2>Process & Documentation</h2>

    <h3>Level, Cinematic, and AI Development</h3>
    <p>
      My process combined layout planning, blockout iteration, set dressing, cinematic sequencing,
      and systems implementation. Since the project required both design and programming responsibilities,
      I focused on keeping the level structure organized while connecting gameplay moments to enemy AI,
      props, and cinematic triggers.
    </p>

    <ul>
      <li>Planned the level through sketches and layout documentation.</li>
      <li>Iterated blockouts to refine pathing, line of sight, and area readability.</li>
      <li>Used level streaming to organize and optimize the environment.</li>
      <li>Implemented enemy AI, props, torches, and gameplay systems to populate the city.</li>
      <li>Created cinematic sequences and blended them into gameplay flow.</li>
    </ul>

    <div class="pdf-viewer-box">
      <iframe
        class="pdf-viewer"
        src="{{ '/dmm-design-doc.pdf' | relative_url }}">
      </iframe>

      <a
        href="{{ '/dmm-design-doc.pdf' | relative_url }}"
        target="_blank"
        rel="noopener noreferrer"
        class="doc-button">
        Open Full Design Document →
      </a>
    </div>
  </div>

  <!-- LEARNINGS -->
  <div class="section">
    <h2>Conclusion & Learnings</h2>
    <p>
      David's Mighty Men strengthened my ability to work across multiple disciplines in Unreal Engine:
      level design, cinematic design, level streaming, set dressing, and AI systems. The biggest challenge
      was keeping the level navigable and readable while also supporting combat, cinematic beats, and technical optimization.
    </p>

    <h3>Knowledge Gained</h3>
    <ul>
      <li>Improved understanding of city layout, scale, and navigable player flow.</li>
      <li>More experience with blockout iteration and level readability.</li>
      <li>Stronger use of Level Sequencer, camera blending, and cinematic timing.</li>
      <li>Hands-on experience implementing Behavior Trees, AI Perception, and EQS-based systems.</li>
      <li>Better understanding of level streaming for organization and optimization.</li>
    </ul>

    <h3>Areas for Growth</h3>
    <ul>
      <li>Continue improving documentation of encounter flow and enemy placement.</li>
      <li>Add more annotated before/after comparisons from blockout to final environment.</li>
      <li>Refine cinematic-to-gameplay transitions for smoother player control handoff.</li>
      <li>Further optimize large city areas through streaming and sublevel organization.</li>
    </ul>
  </div>

  <a class="back" href="./index.html">← Back to Projects Page</a>

</div>
