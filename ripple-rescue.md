---
layout: default
title: Ripple Rescue - Dev Singh
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
  color: #60a5fa;
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
    <a href="./index.html">Projects</a> / Ripple Rescue
  </div>

  <div class="hero">
    <div class="kicker">Mobile Puzzle Game · Level Designer · Cinematic Designer</div>
    <h1>Ripple Rescue</h1>
    <p>
      A top-down mobile puzzle game focused on replayability, difficulty scaling,
      mechanic introduction, and satisfying level completion.
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
      Ripple Rescue challenged me to think differently about level design. Instead of building large,
      open environments, I designed compact mobile puzzle levels that needed to be readable, replayable,
      and satisfying to beat.
    </p>

    <p>
      As a level and cinematic designer, my goal was to create levels that guided the player without
      solving the puzzle for them. Each level needed to feel fair, but still give the player a sense of
      accomplishment through trial, problem-solving, and execution.
    </p>

    <div class="callout-grid">
      <div class="callout">
        <h4>Role</h4>
        <p>Level Designer / Cinematic Designer</p>
      </div>

      <div class="callout">
        <h4>Genre</h4>
        <p>Top-Down Mobile Puzzle Game</p>
      </div>

      <div class="callout">
        <h4>Focus</h4>
        <p>Replayability, Difficulty Scaling, Learning Curve</p>
      </div>
    </div>
  </div>

  <!-- LEVEL GOALS -->
  <div class="section">
    <h2>Level Goals</h2>
    <ul>
      <li>Create puzzle levels that were satisfying to complete through observation and trial-and-error.</li>
      <li>Guide players toward the correct direction without making the solution feel obvious.</li>
      <li>Scale difficulty across easy, medium, and hard levels.</li>
      <li>Introduce new mechanics clearly, especially mechanics like Lock and Key.</li>
      <li>Design levels with replayability and mobile-friendly readability in mind.</li>
    </ul>
  </div>

  <!-- DESIGN FOCUS -->
  <div class="section">
    <h2>Design Focus</h2>
    <p>
      Designing for mobile puzzle gameplay meant prioritizing clarity, pacing, and fast readability.
      Each level needed to communicate its goal quickly, while still leaving enough challenge for the
      player to feel like they solved it themselves.
    </p>

    <div class="image-grid">
      <img src="{{ '/ripple-design-01.png' | relative_url }}" class="image" alt="Ripple Rescue puzzle layout example">
      <img src="{{ '/ripple-design-02.png' | relative_url }}" class="image" alt="Ripple Rescue level design example">
    </div>
  </div>

  <!-- BEAT BREAKDOWN -->
  <div class="section">
    <h2>Design Breakdown</h2>

    <div class="beat">
      <div class="beat-number">Focus 01</div>
      <h3>Replayability</h3>
      <p>
        <strong>Design Intent:</strong> Build levels that players could retry quickly without frustration,
        while still feeling rewarded when they improved their solution.
      </p>
      <ul>
        <li>Kept level layouts readable at a glance for mobile play.</li>
        <li>Designed challenge around player decision-making instead of confusion.</li>
        <li>Supported trial-and-error loops that felt fast and satisfying.</li>
      </ul>
      <img src="{{ '/ripple-beat-01.png' | relative_url }}" class="image" alt="Ripple Rescue replayability example">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 02</div>
      <h3>Layout & Guiding</h3>
      <p>
        <strong>Design Intent:</strong> Lead the player in the right direction while still preserving
        the feeling that they solved the puzzle themselves.
      </p>
      <ul>
        <li>Used layout direction to suggest possible routes.</li>
        <li>Balanced guidance with challenge so solutions did not feel handed to the player.</li>
        <li>Created levels that felt satisfying whether solved immediately or through repeated attempts.</li>
      </ul>
      <img src="{{ '/ripple-beat-02.png' | relative_url }}" class="image" alt="Ripple Rescue guiding example">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 03</div>
      <h3>Difficulty Scaling</h3>
      <p>
        <strong>Design Intent:</strong> Make sure medium levels properly bridged the gap between easy and hard
        levels instead of feeling too simple or too punishing.
      </p>
      <ul>
        <li>Created a learning curve that introduced challenge gradually.</li>
        <li>Adjusted puzzle complexity based on expected player understanding.</li>
        <li>Used medium levels as teaching spaces for upcoming harder challenges.</li>
      </ul>
      <img src="{{ '/ripple-beat-03.png' | relative_url }}" class="image" alt="Ripple Rescue difficulty scaling example">
    </div>

    <div class="beat">
      <div class="beat-number">Focus 04</div>
      <h3>Introducing Lock & Key</h3>
      <p>
        <strong>Design Intent:</strong> Introduce the Lock and Key mechanic in a way that felt tutorial-like
        without becoming boring or unnecessary.
      </p>
      <ul>
        <li>Designed a medium-difficulty level around teaching the mechanic naturally.</li>
        <li>Ensured the mechanic felt worth engaging with instead of feeling like a forced tutorial.</li>
        <li>Balanced clarity and challenge so the player could learn through play.</li>
      </ul>
      <img src="{{ '/ripple-beat-04.png' | relative_url }}" class="image" alt="Ripple Rescue lock and key mechanic">
    </div>
  </div>

  <!-- GALLERY -->
  <div class="section">
    <h2>Image Gallery</h2>

    <div class="image-grid">
      <img src="{{ '/ripple-gallery-01.png' | relative_url }}" class="image" alt="Ripple Rescue gallery image 1">
      <img src="{{ '/ripple-gallery-02.png' | relative_url }}" class="image" alt="Ripple Rescue gallery image 2">
      <img src="{{ '/ripple-gallery-03.png' | relative_url }}" class="image" alt="Ripple Rescue gallery image 3">
      <img src="{{ '/ripple-gallery-04.png' | relative_url }}" class="image" alt="Ripple Rescue gallery image 4">
    </div>
  </div>

  <!-- PROCESS -->
  <div class="section">
    <h2>Process & Documentation</h2>

    <h3>Level Design Process</h3>
    <p>
      My process centered on defining the purpose of each level before building it. I focused on how players would
      read the layout, what mechanic or idea the level was teaching, and how the level fit into the larger difficulty curve.
    </p>

    <ul>
      <li>Designed levels around replayability and satisfying completion.</li>
      <li>Balanced easy, medium, and hard level difficulty progression.</li>
      <li>Introduced new mechanics through playable level scenarios.</li>
      <li>Focused on layout clarity and player-guided problem solving.</li>
    </ul>

    <div class="pdf-viewer-box">
      <iframe
        class="pdf-viewer"
        src="{{ '/ripple-design-doc.pdf' | relative_url }}">
      </iframe>

      <a
        href="{{ '/ripple-design-doc.pdf' | relative_url }}"
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
      Ripple Rescue helped me understand how much level design changes when designing for a mobile puzzle format.
      Instead of relying on large-scale exploration or environmental spectacle, the challenge was creating small,
      readable levels that could be replayed quickly and still feel satisfying to solve.
    </p>

    <h3>Knowledge Gained</h3>
    <ul>
      <li>Stronger understanding of difficulty scaling across multiple level tiers.</li>
      <li>More experience introducing mechanics through level design instead of direct explanation.</li>
      <li>Improved ability to design for fast readability and short replay loops.</li>
      <li>Better understanding of how player satisfaction comes from guided problem-solving.</li>
    </ul>

    <h3>Areas for Growth</h3>
    <ul>
      <li>Add annotated level diagrams explaining player pathing and puzzle logic.</li>
      <li>Improve documentation around difficulty progression between level sets.</li>
      <li>Continue refining how new mechanics are introduced without feeling like forced tutorials.</li>
    </ul>
  </div>

  <a class="back" href="./index.html">← Back to Projects Page</a>

</div>
