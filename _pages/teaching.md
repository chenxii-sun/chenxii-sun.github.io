---
layout: page
title: Teaching
permalink: /teaching/
nav: true
nav_order: 3
description: ""
---

<style>
:root {
  --teaching-purple: #552D98;
  --teaching-orange: #E69735;
  --teaching-orange-light: rgba(230, 151, 53, 0.18);
  --teaching-border: #eadfbf;
  --teaching-text-light: #6f6f6f;
}

.teaching-page {
  margin-top: 0.5rem;
}

.teaching-title {
  font-size: 3rem;
  font-weight: 400;
  margin-bottom: 2rem;
}

.teaching-section {
  margin-bottom: 2.8rem;
}

.teaching-heading {
  display: flex;
  align-items: center;
  font-size: 1.3rem;
  font-weight: 700;
  color: var(--teaching-purple);
  margin-bottom: 0.8rem;
}

.teaching-heading::before {
  content: "";
  width: 7px;
  height: 24px;
  background: var(--teaching-purple);
  border-radius: 4px;
  margin-right: 12px;
}

.teaching-divider {
  border-bottom: 1px solid var(--teaching-border);
  margin-bottom: 0.9rem;
}

.school-name {
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--teaching-purple);
  margin-bottom: 0.8rem;
}

.course-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  border: 1px solid #eddde9;
  border-left: 4px solid var(--teaching-orange);
  border-radius: 10px;
  padding: 0.9rem 1rem;
  margin-bottom: 0.8rem;
  background: rgba(255,255,255,0.72);
}

.course-info {
  flex: 1;
  line-height: 1.45;
}

.course-code {
  font-weight: 700;
}

.course-meta {
  color: var(--teaching-text-light);
}

.term-badge {
  white-space: nowrap;
  border: 1px solid #dfc375;
  color: #8a6400;
  background: #fbf4df;
  border-radius: 999px;
  padding: 0.35rem 0.8rem;
  font-size: 0.88rem;
  font-weight: 600;
}

.note-box {
  margin-top: 1rem;
  padding: 0.85rem 1rem;
  border-left: 4px solid var(--teaching-purple);
  background: rgba(85, 45, 152, 0.05);
  border-radius: 8px;
  font-size: 0.96rem;
}

@media (max-width: 700px) {
  .course-card {
    flex-direction: column;
    align-items: flex-start;
  }

  .term-badge {
    white-space: normal;
  }
}
</style>

<div class="teaching-page">

  <div class="teaching-title">Teaching</div>

  <div class="teaching-section">
    <div class="teaching-heading">Teaching Assistant</div>
    <div class="teaching-divider"></div>

    <div class="school-name">CUHK Business School, The Chinese University of Hong Kong</div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">DOTE6200:</span>
        Supply Chain Sustainability Management
        <span class="course-meta">(Master course)</span>
      </div>
      <div class="term-badge">2025, 2026</div>
    </div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">FEMBA6122:</span>
        Data, Models and Decisions
        <span class="course-meta">(FEMBA course)</span>
      </div>
      <div class="term-badge">2025, 2026</div>
    </div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">DOTE6330:</span>
        Probability and Mathematical Statistics
        <span class="course-meta">(FMBA course)</span>
      </div>
      <div class="term-badge">2024</div>
    </div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">DOTE2040:</span>
        Business Analytics
        <span class="course-meta">(Undergraduate course)</span>
      </div>
      <div class="term-badge">2024</div>
    </div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">DOTE5410:</span>
        Operations Management
        <span class="course-meta">(MBA course)</span>
      </div>
      <div class="term-badge">2022, 2023</div>
    </div>

    <div class="course-card">
      <div class="course-info">
        <span class="course-code">DSME4020:</span>
        Decision Modeling and Analytics
        <span class="course-meta">(Undergraduate course)</span>
      </div>
      <div class="term-badge">2022</div>
    </div>

    <div class="note-box">
      Teaching evaluation: <strong>5.43 / 6.00</strong>
    </div>
  </div>

</div>
