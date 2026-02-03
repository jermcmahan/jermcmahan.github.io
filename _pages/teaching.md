---
layout: page
permalink: /Teaching/
title: Teaching
description: #On this page, you can find each course I've worked on as well as select materials from each course.
nav: true
nav_order: 3
#toc:
#  sidebar: right
---

## Teaching Summary 

<div class="row" style="margin-top: 10px; margin-bottom: 40px;">
    
    <div class="col-sm-7">
        <p>
            My teaching experience ranges from Course Assistant to Instructor, spanning positions at <strong>UIUC</strong>, <strong>UW-Madison</strong>, and the <strong>New Horizons Summer School</strong> (sponsored by SIGACT and TTIC).
        </p>

        <p>
            My teaching philosophy centers on breaking down complex topics to simplify learning. My favorite approach to building intuition is through the <strong>power of analogy</strong>: relating a new, abstract topic to one the students already understand.
        </p>

        <p>
            I strongly believe in <strong>open access</strong> to education and am committed to making my course materials publicly available.
        </p>
    </div>

<div class="col-sm-5">
    <div class="card h-100" style="border: 1px solid #e0e0e0; border-left: 4px solid var(--global-theme-color); border-radius: 15px">
      
      <div class="card-body">
        <h6 class="card-title" style="font-weight: bold; color: var(--global-header-color);">Courses Taught</h6>
        
        <ul style="font-size: 1rem; padding-left: 1.2rem; margin-bottom: 0;">
            <li class="card-text" style="font-size: 1rem; margin-bottom: 8px;">Game Theory, Optimization & Learning</li>
            <li class="card-text" style="font-size: 1rem; margin-bottom: 8px;">Introduction to Algorithms</li>
            <li class="card-text" style="font-size: 1rem; margin-bottom: 8px;">Introduction to Artificial Intelligence</li>
            <li class="card-text" style="font-size: 1rem; margin-bottom: 8px;">Introduction to Data Science</li>
            <li class="card-text" style="font-size: 1rem; margin-bottom: 8px;">Introduction to Optimization</li>
            <li class="card-text" style="font-size: 1rem;">Algorithms and Models of Computation</li>
        </ul>
        
      </div>
    </div>
</div>

</div>

## Selected Course Materials

<div class="row" style="margin-top: 20px; margin-bottom: 20px;">
  <div class="col-sm-6">
    <div class="card h-100" style="border: 1px solid #e0e0e0; border-left: 4px solid var(--global-theme-color); border-radius: 15px">
      <div class="card-body">
        <h6 class="card-title" style="font-weight: bold; color: var(--global-header-color);">Algorithms Lecture Recordings</h6>
        <p class="card-text" style="font-size: 0.9rem;">
            Complete lecture series from my time as instructor for <i>Introduction to Algorithms</i> at UW-Madison:
        </p>
        <a href="https://youtube.com/playlist?list=PLJq-M8V1ZfiYJXHEnwiskcrg5xyc4MTgi&si=vkx1t0R9uR0758rg" target="_blank" class="btn btn-sm" style="color: var(--global-theme-color); border-color: var(--global-theme-color);">
          <i class="fab fa-youtube"></i> Watch Lectures
        </a>
      </div>
    </div>
  </div>

  <div class="col-sm-6">
    <div class="card h-100" style="border: 1px solid #e0e0e0; border-left: 4px solid var(--global-theme-color); border-radius: 15px">
      <div class="card-body">
        <h6 class="card-title" style="font-weight: bold; color: var(--global-header-color);">MARL Theory Notes</h6>
        <p class="card-text" style="font-size: 0.9rem;">
            Lecture notes and slides from the Multi-Agent RL module of <i>Game Theory, Optimization & Learning</i> at UW-Madison:
        </p>
        <a href="/assets/pdf/CS839.zip" target="_blank" class="btn btn-sm" style="color: var(--global-theme-color); border-color: var(--global-theme-color);">
          <i class="fas fa-file-archive"></i> Download ZIP
        </a>
      </div>
    </div>
  </div>

</div>

## Courses

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --file teaching --query @* %}

</div>