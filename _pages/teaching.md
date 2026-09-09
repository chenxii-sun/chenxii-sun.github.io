---
layout: page
title: Teaching/Service
permalink: /teaching/
nav: true
nav_order: 3
description: ""
---

<style>
:root {
  --teaching-purple: #552D98;
  --teaching-orange: #E69735;
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

/* Section heading */
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
  margin-bottom: 1rem;
}

/* School */
.school-name {
  font-size: 1.08rem;
  font-weight: 700;
  color: var(--teaching-purple);
  margin-bottom: 0.85rem;
}

/* Course card */
.course-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1.2rem;

  border: 1px solid #eadfea;
  border-left: 4px solid var(--teaching-orange);
  border-radius: 9px;

  padding: 0.85rem 1rem;
  margin-bottom: 0.75rem;

  background: rgba(255, 255, 255, 0.72);
}

.course-info {
  flex: 1;
  min-width: 0;
}

/* Course name and type badge */
.course-main-line {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 0.5rem;

  line-height: 1.45;
}

.course-code {
  font-weight: 700;
}

.course-type-badge {
  display: inline-block;

  padding: 2px 9px;
  border-radius: 999px;

  background: var(--teaching-purple);
  color: #ffffff;

  font-size: 0.72rem;
  font-weight: 600;
  line-height: 1.4;
}

/* Year badge */
.term-badge {
  flex-shrink: 0;
  white-space: nowrap;

  border: 1px solid #dfc375;
  color: #795600;
  background: #fbf4df;

  border-radius: 999px;
  padding: 0.35rem 0.8rem;

  font-size: 0.86rem;
  font-weight: 600;
}

/* Teaching evaluation */
.course-evaluation {
  margin-top: 0.45rem;
  font-size: 0.86rem;
  color: var(--teaching-text-light);
}

.course-evaluation strong {
  color: var(--teaching-purple);
  font-weight: 700;
}
/* Internal service */
.service-section {
  margin-top: 3rem;
}

.service-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1.2rem;

  padding: 0.25rem 0 0.4rem 0;
}

.service-info {
  flex: 1;
}

.service-role {
  font-size: 1rem;
  font-weight: 700;
  line-height: 1.4;
}

.service-unit {
  margin-top: 0.15rem;
  color: var(--teaching-text-light);
  font-size: 0.92rem;
}
  
@media (max-width: 700px) {

  .teaching-title {
    font-size: 2.4rem;
  }

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


  <div class="teaching-section">

    <div class="teaching-heading">
      Teaching Assistant
    </div>

    <div class="teaching-divider"></div>

    <div class="school-name">
      CUHK Business School, The Chinese University of Hong Kong
    </div>


    <!-- DOTE6200 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">DOTE6200:</span>
            Supply Chain Sustainability Management
          </span>

          <span class="course-type-badge">
            MSc
          </span>

        </div>

      </div>

      <div class="term-badge">
        2025, 2026
      </div>

    </div>


    <!-- FEMBA6122 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">FEMBA6122:</span>
            Data, Models and Decisions
          </span>

          <span class="course-type-badge">
            FEMBA
          </span>

        </div>

      </div>

      <div class="term-badge">
        2025, 2026
      </div>

    </div>


    <!-- DOTE6330 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">DOTE6330:</span>
            Probability and Mathematical Statistics
          </span>

          <span class="course-type-badge">
            FMBA
          </span>

        </div>

      </div>

      <div class="term-badge">
        2024
      </div>

    </div>


    <!-- DOTE2040 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">DOTE2040:</span>
            Business Analytics
          </span>

          <span class="course-type-badge">
            Undergraduate
          </span>

        </div>

        <div class="course-evaluation">
          Teaching evaluation:
          <strong>5.43 / 6.00</strong>
        </div>

      </div>

      <div class="term-badge">
        2024
      </div>

    </div>


    <!-- DOTE5410 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">DOTE5410:</span>
            Operations Management
          </span>

          <span class="course-type-badge">
            MBA
          </span>

        </div>

      </div>

      <div class="term-badge">
        2022, 2023
      </div>

    </div>


    <!-- DSME4020 -->
    <div class="course-card">

      <div class="course-info">

        <div class="course-main-line">

          <span>
            <span class="course-code">DSME4020:</span>
            Decision Modeling and Analytics
          </span>

          <span class="course-type-badge">
            Undergraduate
          </span>

        </div>

      </div>

      <div class="term-badge">
        2022
      </div>

    </div>

  </div>

<div class="teaching-section service-section">

  <div class="teaching-heading">
    Internal Service
  </div>

  <div class="teaching-divider"></div>

  <div class="school-name">
    The Chinese University of Hong Kong
  </div>

  <div class="service-row">

    <div class="service-info">

      <div class="service-role">
        Studen Seminar Coordinator
      </div>

      <div class="service-unit">
        Department of Decisions, Operations and Technology
      </div>

    </div>

    <div class="term-badge">
      2026
    </div>

  </div>

</div>


