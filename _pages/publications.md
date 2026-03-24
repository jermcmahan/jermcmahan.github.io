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

<style>
  /* 1. Style all H3s on this page (Conference Papers, Manuscripts) */
  h3 {
    font-size: 0.9rem;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: var(--global-theme-color); /* Keeps your theme consistency */
    
    margin-top: 30px;    /* Space above the section */
    margin-bottom: 10px; /* Space below (before the year) */
    
    border-bottom: 1px solid var(--global-divider-color);
    padding-bottom: 5px;
  }
</style>

## Research Summary

<div class="research-summary" style="margin-bottom: 40px;">
  <p> 
    My research aims to overcome intractability barriers in <strong>decision-making under uncertainty</strong> to enable <span style="color: var(--global-theme-color); font-weight: bold;">capable and reliable AI agents</span>. Capability - solving constrained, combinatorial, and multi-agent problems - and reliablity - operating safely and robustly - both face <i>uncertainty</i> and <i>computational complexity</i>. I tackle both by leveraging <strong>machine learning</strong> to handle uncertainty while incorporating <strong>worst-case algorithm design</strong> to ensure performance and safety. This approach yielded answers to long-standing open questions in constrained and multi-agent reinforcement learning.  
 My research spans two interconnected directions:
  </p>

  <div class="row mt-4">
    
    <div class="col-sm-6" style="padding-right: 15px;">
      <h5 style="color: var(--global-theme-color); font-weight: bold; margin-bottom: 15px;">
        <i class="fas fa-network-wired" style="margin-right: 8px; opacity: 0.8;"></i> 
        Constrained Agent Planning
      </h5>
      <ul style="font-size: 1rem; line-height: 1.4; padding-left: 20px;">
        <li style="margin-bottom: 10px;">
          <strong>Constrained MDPs:</strong> Designed the first polynomial-time approximation and learning algorithms for general Constrained MDPs.
        </li>
        <li style="margin-bottom: 10px;">
          <strong>Stochastic Search:</strong> Developed the first adaptive approximation algorithms for correlated Pandora’s Box problems.
        </li>
        <li>
          <strong>Online Scheduling:</strong> Established the state-of-the-art competitive ratio for the multilevel aggregation with deadlines.
        </li>
      </ul>
    </div>

    <div class="col-sm-6" style="padding-left: 15px;">
      <h5 style="color: var(--global-theme-color); font-weight: bold; margin-bottom: 15px;">
        <i class="fas fa-chess" style="margin-right: 8px; opacity: 0.8;"></i> 
        Robust Multi-Agent Systems
      </h5>
      <ul style="font-size: 1rem; line-height: 1.4; padding-left: 20px;">
        <li style="margin-bottom: 10px;">
          <strong>Safe & Robust Equilibria:</strong> Designed the first polynomial-time planning and learning algorithms for computing anytime-constrained, adversarial-defense, and uncertainty-robust equilibria in Markov Games.
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
    <p> 
    To see how these topics connect and future directions, check out my <a href="/assets/pdf/Research_Statement.pdf" target="_blank">Research Statement</a>.
  </p>
</div>


## Papers

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

## Invited Talks

<div class="publications">

{% bibliography --file talks --query @*%}

</div>