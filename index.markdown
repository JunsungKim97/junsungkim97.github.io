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
      <strong>Yonsei University</strong>
      <div class="meta">Ph.D. student in Electrical and Electronic Engineering, 2024 - Present</div>
      <div class="meta">Advisor: Prof. Won Woo Ro</div>
    </div>
    <div class="card">
      <strong>Yonsei University</strong>
      <div class="meta">M.S. in Electrical and Electronic Engineering, 2022 - 2024</div>
      <div class="meta">Advisor: Prof. Won Woo Ro</div>
    </div>
    <div class="card">
      <strong>Yonsei University</strong>
      <div class="meta">B.S. in Electrical and Electronic Engineering, 2016 - 2022</div>
      <div class="meta">Advisor: Prof. Won Woo Ro</div>
    </div>
  </section>

  <section id="experience">
    <h2 class="section-title">Research Experience</h2>
    <div class="card">
      <strong>University of California, San Diego (UCSD)</strong>
      <div class="meta">Visiting Scholar in Computer Science & Engineering, Feb. 2025 - Feb. 2026</div>
      <div class="meta">Advisor: Prof. Yufei Ding</div>
      <!-- <div>Add 1-2 lines about what you worked on.</div> -->
    </div>
  </section>

  <section id="publications">
    <h2 class="section-title">Publications</h2>
    <div class="card">
      <strong>(To appear) Reducing Page Faults via Invalidation-based Mapping Propagation in Multi-GPU Systems</strong>
      <div class="authors"><u>Junsung Kim</u>, Dongho Ha, Sungwoo Kim, Wonho Cho, Sungbin Kim, Yufei Ding, and Won Woo Ro</div>
      <div class="meta">International Symposium on Computer Architecture (ISCA), 2026</div>
      <!-- <div>Short description and link placeholders (PDF / Code / Bib).</div> -->
    </div>
  </section>

  <section id="moments">
    <h2 class="section-title">Moments</h2>
    <p>
      You can add quick updates, photos, or short notes here.
    </p>
  </section>
</div>
