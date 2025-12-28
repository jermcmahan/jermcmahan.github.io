---
layout: page
permalink: /Research/
title: Research
description: #On this page, you can find each of my papers and invited talks.
nav: true
nav_order: 2
#toc:
#  sidebar: left
---

---
# Research Summary

<div class="research-summary" style="margin-bottom: 40px;">
  <p> 
    My research investigates the theoretical foundations of optimization and decision-making in uncertain environments. My work aims to overcome intractability barriers prevalent throughout modern problems via two core directions:
  </p>

  <div class="row mt-4">
    
    <div class="col-sm-6" style="padding-right: 15px;">
      <h5 style="color: var(--global-theme-color); font-weight: bold; margin-bottom: 15px;">
        <i class="fas fa-network-wired" style="margin-right: 8px; opacity: 0.8;"></i> 
        Optimization under Uncertainty
      </h5>
      <ul style="font-size: 1rem; line-height: 1.4; padding-left: 20px;">
        <li style="margin-bottom: 10px;">
          <strong>Constrained RL:</strong> Designed the first polynomial-time approximation algorithms for general Constrained MDPs.
        </li>
        <li style="margin-bottom: 10px;">
          <strong>Stochastic Optimization:</strong> Developed the first adaptive approximation algorithms for correlated Pandora’s Box problems.
        </li>
        <li>
          <strong>Online Scheduling:</strong> Established the state-of-the-art competitive ratio for the multilevel aggregation with deadlines.
        </li>
      </ul>
    </div>

    <div class="col-sm-6" style="padding-left: 15px;">
      <h5 style="color: var(--global-theme-color); font-weight: bold; margin-bottom: 15px;">
        <i class="fas fa-chess" style="margin-right: 8px; opacity: 0.8;"></i> 
        Game-Theoretic MARL
      </h5>
      <ul style="font-size: 1rem; line-height: 1.4; padding-left: 20px;">
        <li style="margin-bottom: 10px;">
          <strong>Safe & Robust Equilibria:</strong> Designed the first polynomial-time algorithms for computing anytime-constrained, adversarial-defense, and uncertainty-robust equilibria in Markov Games.
        </li>
        <li style="margin-bottom: 10px;">
          <strong>Adversarial Attacks:</strong> Characterized optimal poisoning and misinformation attacks on MARL agents.
        </li>
        <li>
          <strong>Incentivized Exploration:</strong> Designed the first constant-regret mechanisms to align myopic agents with social welfare goals.
        </li>
      </ul>
    </div>

  </div>
</div>

---
# Papers

Below, you can find each of my papers. <i>Unless otherwise noted, author names are ordered by contribution.</i>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}


### Conference Papers

<div class="publications">

{% bibliography --query @*[keywords=conference]%}

</div>


### Preprints and Working Papers

<div class="publications">

{% bibliography --query @*[keywords=preprint]%}

</div>


### Theses and Technical Reports

<div class="publications">

{% bibliography --query @*[keywords=thesis]%}

</div>

---
# Invited Talks

<div class="publications">

{% bibliography --file talks --query @*%}

</div>