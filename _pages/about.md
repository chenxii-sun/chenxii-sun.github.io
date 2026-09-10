---
layout: page
title: Home
permalink: /
nav: true
nav_order: 1
description: "Chenxi Sun - PhD student in Operations Management at CUHK Business School"
---

<style>
:root {
  --home-purple: #552D98;
  --home-orange: #E69735;
  --home-orange-light: rgba(230, 151, 53, 0.35);
  --home-text-light: #777777;
}

/* Overall page */
.home-page {
  margin-top: 0.8rem;
}

/* Name */
.home-name {
  font-size: 3.6rem;
  font-weight: 400;
  line-height: 1.1;
  margin-bottom: 0.8rem;
  letter-spacing: -0.02em;
}

/* Motto */
.home-motto {
  font-size: 1.12rem;
  color: var(--home-text-light);
  margin-bottom: 2rem;
}

/* Divider */
.home-divider {
  width: 100%;
  height: 1px;
  background: linear-gradient(
    to right,
    var(--home-orange-light),
    rgba(230, 151, 53, 0.08)
  );
  margin-bottom: 2.6rem;
}

/* Main two-column layout */
.home-content {
  display: grid;
  grid-template-columns: minmax(0, 1.65fr) minmax(260px, 0.85fr);
  gap: 3.5rem;
  align-items: start;
}

/* Introduction */
.home-intro {
  font-size: 1.06rem;
  line-height: 1.72;
}

.home-intro p {
  margin-bottom: 1.3rem;
}

/* Professor links */
.prof-link {
  color: var(--home-purple) !important;
  font-weight: 500;
  text-decoration: none;
}

.prof-link:hover {
  color: var(--home-orange) !important;
  text-decoration: underline;
}

/* Optional emphasis */
.research-emphasis {
  color: var(--home-purple);
  font-weight: 500;
}

/* Profile image */
.home-photo-wrapper {
  width: 100%;
}

.home-photo {
  display: block;
  width: 100%;
  max-width: 390px;
  margin-left: auto;
  border-radius: 7px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.14);
}

/* Mobile */
@media (max-width: 800px) {

  .home-name {
    font-size: 2.8rem;
  }

  .home-content {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .home-photo-wrapper {
    order: -1;
  }

  .home-photo {
    max-width: 320px;
    margin-left: 0;
  }
}
</style>


<div class="home-page">

  <div class="home-name">
    Chenxi Sun
  </div>

  <div class="home-motto">
    Our challenge is bigger, but our will is greater.
  </div>

  <div class="home-divider"></div>


  <div class="home-content">

    <!-- LEFT: INTRODUCTION -->
    <div class="home-intro">

      <p>
        I am a final-year PhD student in Operations Management at CUHK Business School,
        where I am extremely fortunate to be advised by
        <a
          class="prof-link"
          href="https://www.bschool.cuhk.edu.hk/staff/zhou-sean-xiang/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Professor Sean Zhou
        </a>.
        I have also benefited greatly from the guidance and mentorship of
        <a
          class="prof-link"
          href="https://www.bschool.cuhk.edu.hk/staff/gong-xiting/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Professor Xiting Gong
        </a>.
      </p>

      <p>
        Before joining CUHK, I received my bachelor's and master's degrees from
        the School of Information Management and Engineering at Shanghai University
        of Finance and Economics, where I was fortunate to be advised by
        <a
          class="prof-link"
          href="https://riis.sufe.edu.cn/51/e1/c10430a152033/page.htm"
          target="_blank"
          rel="noopener noreferrer"
        >
          Professor Chaolin Yang
        </a>.
      </p>

      <p>
        My research designs simple, implementable heuristic policies for complex
        operational problems whose optimal solutions are intractable or impractical
        to deploy, and establishes performance guarantees for these policies across
        different regimes. I am drawn to problems closely tied to everyday business
        practice, and I aim to provide solutions that firms can readily adopt while
        studying emerging business models.
      </p>

      <p>
        My research interests include
        <span class="research-emphasis">inventory management</span>,
        <span class="research-emphasis">supply chain management</span>,
        <span class="research-emphasis">stochastic inventory theory and its applications</span>,
        and the
        <span class="research-emphasis">operations–marketing interface</span>.
        I'm happy to discuss related topics and open to potential collaborations.
        Feel free to reach out! I am on the 2026-2027 academic job market.
      </p>

    </div>


    <!-- RIGHT: PHOTO -->
    <div class="home-photo-wrapper">

      <img
        class="home-photo"
        src="{{ '/assets/img/prof_pic.jpg' | relative_url }}"
        alt="Chenxi Sun"
      >

    </div>

  </div>

</div>
