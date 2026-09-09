---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
description: ""
---

<style>
:root {
  --research-purple: #552D98;
  --research-orange: #E69735;
  --research-orange-light: rgba(230, 151, 53, 0.35);
}

.research-section {
  margin-top: 2.2rem;
  margin-bottom: 3rem;
}

.research-heading {
  display: flex;
  align-items: center;
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 1.2rem;
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 0.6rem;
}

.research-heading::before {
  content: "";
  width: 7px;
  height: 24px;
  background: var(--research-purple);
  border-radius: 4px;
  margin-right: 12px;
}

.research-card {
  position: relative;
  border: 1px solid #e1e1e1;
  border-top: 3px solid var(--research-orange);
  border-radius: 9px;
  padding: 1.25rem 1.3rem 1rem 5.2rem;
  margin-bottom: 1.2rem;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.04);
}

.paper-tag {
  position: absolute;
  left: 1.2rem;
  top: 1.25rem;
  min-width: 50px;
  text-align: center;
  padding: 2px 9px;
  border-radius: 14px;
  background: var(--research-purple);
  color: white;
  font-size: 0.8rem;
  font-weight: 700;
  border: 1px solid var(--research-orange);
}

.paper-title {
  font-size: 1.08rem;
  font-weight: 600;
  line-height: 1.35;
  margin-bottom: 0.25rem;
}

.paper-authors {
  font-size: 0.95rem;
  margin-bottom: 0.35rem;
}

.paper-authors a {
  color: var(--research-purple);
  text-decoration: underline;
}

.paper-status {
  color: #777;
  font-size: 0.95rem;
  margin-bottom: 0.7rem;
}

.paper-status em {
  color: #444;
}

.paper-buttons {
  margin: 0.5rem 0 0.8rem 0;
}

.paper-button {
  display: inline-block;
  padding: 3px 9px;
  margin-right: 5px;
  border: 1px solid #333;
  border-radius: 4px;
  color: inherit;
  font-size: 0.78rem;
  text-decoration: none;
}

.paper-button:hover {
  background: #f3f3f3;
  text-decoration: none;
}

.research-details {
  border-top: 1px solid var(--research-orange-light);
  padding-top: 0.7rem;
  margin-top: 0.6rem;
}

.research-details summary {
  cursor: pointer;
  color: var(--research-purple);
  font-weight: 600;
  font-size: 0.88rem;
  list-style: none;
}

.research-details summary::-webkit-details-marker {
  display: none;
}

.research-details p {
  margin-top: 0.8rem;
  margin-bottom: 0.2rem;
  line-height: 1.55;
  font-size: 0.93rem;
}

@media (max-width: 700px) {
  .research-card {
    padding: 3.4rem 1rem 1rem 1rem;
  }

  .paper-tag {
    left: 1rem;
    top: 1rem;
  }
}
</style>


<div class="research-section">

  <div class="research-heading">
    Papers Under Revision / Review
  </div>


  <div class="research-card">

    <div class="paper-tag">W1</div>

    <div class="paper-title">
      Remanufacturing Inventory System with Demand-Dependent Returns:
      Optimality Analysis and Approximations
    </div>

    <div class="paper-authors">
      Chenxi Sun, Zhijie Tao, Xuefeng Gao, and Sean Zhou
    </div>

    <div class="paper-status">
      Minor revision at <em>Operations Research</em>
    </div>

    <div class="paper-buttons">
      <a
        class="paper-button"
        href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5038327"
        target="_blank"
        rel="noopener noreferrer"
      >
        SSRN
      </a>
    </div>

    <details class="research-details">
      <summary>Research details</summary>

      <p>
        We study an infinite-horizon periodic-review remanufacturing inventory
        system with random demand and product return. The quantity of returned
        products each period depends on historical demands following a
        distributed lag model. A firm operating the system remanufactures
        product returns into a serviceable product to fulfill customer demand.
        When needed, the serviceable product can also be manufactured or ordered.
        Manufacturing and remanufacturing have different lead times. The firm
        decides the manufacturing quantity each period to minimize the expected
        long-run average cost of inventory holding, demand backlogging, and
        manufacturing.
      </p>

      <p>
        We first establish the existence of a stationary optimal policy under
        the long-run average-cost criterion using the vanishing discount factor
        approach together with a coupling argument. Via state-space reduction,
        we further prove that the optimal policy is a forecast-adjusted
        base-stock (FABS) policy when the maximum return lag is shorter than the
        manufacturing lead time. When the maximum return lag is longer than the
        manufacturing lead time, the optimal policy becomes a state-dependent
        base-stock policy. For the latter case, we show that the FABS policy
        becomes asymptotically optimal as the unit backlogging cost becomes large.
      </p>

      <p>
        We further develop simple approximate base-stock levels for implementing
        the FABS policy and numerically demonstrate their effectiveness. Two
        extensions are examined: one with random coefficients in the return
        model and another with separate core inventory and remanufacturing
        decisions.
      </p>
    </details>

  </div>


  <div class="research-card">

    <div class="paper-tag">W2</div>

    <div class="paper-title">
      Base-stock Policies in Backlogging Inventory Systems with Stochastic
      Lead Times: New Results and Insights
    </div>

    <div class="paper-authors">
      Chenxi Sun and Xiting Gong
    </div>

    <div class="paper-status">
      Under review at <em>Operations Research</em>
    </div>

    <div class="paper-buttons">
      <a
        class="paper-button"
        href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7367439"
        target="_blank"
        rel="noopener noreferrer"
      >
        SSRN
      </a>
    </div>

    <details class="research-details">
      <summary>Research details</summary>

      <p>
        We study periodic-review backlogging inventory systems with exogenous
        stochastic lead times. Although base-stock (BS) policies that maintain a
        constant inventory position are optimal when orders do not cross in
        transit, their performance under lead-time processes that permit
        crossover remains poorly understood.
      </p>

      <p>
        We provide new insights into the effectiveness of BS policies in such
        settings. First, we derive an upper bound on the optimality gap of a BS
        policy that explicitly captures the impact of order crossover. The bound
        implies that the BS policy is optimal when order crossover is absent or
        when demand is bounded and the unit backlogging cost is sufficiently
        large. Second, under a mild regularity condition, we establish the
        asymptotic optimality of the BS policy as the unit backlogging cost grows
        large. Third, we show that the difference between the optimality gaps of
        the optimal BS policy under stochastic and deterministic demand is
        bounded by a term proportional to the coefficient of variation of demand.
      </p>
    </details>

  </div>

</div>


<div class="research-section">

  <div class="research-heading">
    Working Papers
  </div>

  <div class="research-card">

    <div class="paper-tag">W3</div>

    <div class="paper-title">
      The Impact of Secondary Markets on Selling Blind Boxes with Set Bonuses
    </div>

    <div class="paper-authors">
      Chenxi Sun, Yinbo Feng, and Chaolin Yang
    </div>

    <div class="paper-status">
      Working paper
    </div>

    <div class="paper-buttons">
      <a
        class="paper-button"
        href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4284733"
        target="_blank"
        rel="noopener noreferrer"
      >
        SSRN
      </a>
    </div>

    <details class="research-details">
      <summary>Research details</summary>

      <p>
        We develop an analytical framework in which a firm sells a blind box,
        from which two horizontally differentiated items are randomly drawn.
        Two types of customers have different valuations for the two items.
        A customer gains an extra utility, called a set bonus, if she obtains
        a complete set of items; hence, she may repeat purchases until her
        expected utility is maximized.
      </p>

      <p>
        We study and compare the selling of blind boxes in two settings, with
        and without a secondary market. We prove that with the secondary market,
        the firm's problem is equivalent to a principal-agent problem. We use
        a linear program and its dual problem to solve the secondary-market
        equilibrium and the firm's profit. We identify two effects of the
        secondary market: the growth effect and the incompatibility effect.
        The former is positive, whereas the latter is negative.
      </p>

      <p>
        We find that the secondary market hurts the firm if and only if
        customers' preferences are highly polarized and the set bonus is
        positive but small. Our main insights continue to hold when the blind
        box contains multiple items.
      </p>
    </details>

  </div>

</div>


<div class="research-section">

  <div class="research-heading">
    Work in Progress
  </div>

  <div class="research-card">

    <div class="paper-tag">W4</div>

    <div class="paper-title">
      Collect, Process, and Sell: Operations of a Smallholder Aggregator
    </div>

    <div class="paper-authors">
      Chenxi Sun, Christopher Thomas Ryan, and Sean Zhou
    </div>

    <div class="paper-status">
      Work in progress
    </div>

    <details class="research-details">
      <summary>Research details</summary>

      <p>
        We study the operational decisions of a smallholder agricultural
        aggregator, including collection, processing, and selling decisions
        under supply, quality, and price uncertainty.
      </p>
    </details>

  </div>

</div>
