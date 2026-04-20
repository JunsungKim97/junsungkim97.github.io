---
layout: default
title: Home
---

<style>
  .home-wrap { max-width: 920px; margin: 0 auto; }
  .top-nav { display: flex; gap: 1.2rem; margin: 0.5rem 0 1.5rem; font-weight: 600; }
  .top-nav a { text-decoration: none; }
  .hero { margin-bottom: 1.75rem; }
  .hero h1 { margin-bottom: 0.35rem; }
  .section-title { margin-top: 2.2rem; margin-bottom: 0.7rem; }
  .card {
    border: 1px solid #e6e6e6;
    border-radius: 10px;
    padding: 0.9rem 1rem;
    margin-bottom: 0.8rem;
    background: #fafafa;
  }
  .meta { color: #666; font-size: 0.95rem; margin-top: 0.2rem; }
</style>

<div class="home-wrap">
  <nav class="top-nav">
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#publications">Publications</a>
    <a href="#moments">Moments</a>
  </nav>

  <section class="hero" id="about">
    <h1>Junsung Kim</h1>
    <p>
      I am interested in building useful products and sharing what I learn.
      This homepage is my personal space for projects, writing, and updates.
    </p>
    <p><strong>Email:</strong> your-email@example.com</p>
  </section>

  <section id="education">
    <h2 class="section-title">Education</h2>
    <div class="card">
      <strong>Your University Name</strong>
      <div class="meta">B.S. in Your Major, 20XX - 20XX</div>
    </div>
  </section>

  <section id="experience">
    <h2 class="section-title">Experience</h2>
    <div class="card">
      <strong>Your Company / Lab</strong>
      <div class="meta">Role, 20XX - Present</div>
      <div>Add 1-2 lines about what you worked on.</div>
    </div>
  </section>

  <section id="publications">
    <h2 class="section-title">Selected Publications</h2>
    <div class="card">
      <strong>Title of Paper or Project</strong>
      <div class="meta">Conference / Venue, Year</div>
      <div>Short description and link placeholders (PDF / Code / Bib).</div>
    </div>
  </section>

  <section id="moments">
    <h2 class="section-title">Moments</h2>
    <p>
      You can add quick updates, photos, or short notes here.
    </p>
  </section>
</div>
