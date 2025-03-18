---
title: "Optimized Thrust Chamber Design via CFD"
date: Mar 2024
category: "personal"  
priority: 3
header_image: "/assets/images/thrust.png" 
description: "A design project to conceive a thrust chamber for LEO payload transport, optimized through iterative CFD analysis."
layout: "project"  
technologies:
  - CFD Analysis
  - SolidWorks
  - Iterative Design
  - Material Science
---

<div class="project-meta">
    <span class="project-date">{{ page.date | date: "%b %Y" }}</span>
</div>

## Project Overview
- Conceived a thrust chamber to transport payloads to Low Earth Orbit within a confined 3m x 1m x 1m space.
- Iteratively refined the design using CFD simulations to optimize fluid dynamics, thrust force, and efficiency.
- Selected Titanium for its strength, lightweight properties, and resistance to extreme conditions.
- Achieved a final design that meets the required thrust force (>1050 kN) and efficiency benchmarks.

---

## Design Process

Through multiple iterations, I adapted the chamber geometry based on CFD cut plots and thrust calculations. The first iteration met the minimum fluid volume but delivered insufficient thrust. Subsequent iterations involved shortening the distance between the chamber neck and outlet, widening the outlet, and ultimately adopting a triangular configuration. The final design, with a thrust force of approximately 1066 kN and an internal volume of 0.56 m³, comfortably meets all design criteria while achieving a high efficiency score.

---

<img src="/assets/images/thrust.png" alt="Thrust Chamber" class="project-image" />

---

## **Project Documentation**
<embed src="/assets/documents/CFD.pdf" width="100%" height="600px" type="application/pdf">

---

<style>

.project-content h1 {
    color: #f0f0f0;  /* Light gray (adjust as needed) */
    font-size: 2.5rem;  /* Adjust for visibility */
    margin-bottom: 10px;
}
  
  .project-meta {
    font-size: 1rem;
    color: #888;
    font-weight: 400;
    margin-bottom: 1rem;
    text-align: left;
}

.project-date {
    display: block;
    font-size: 1rem;
    color: #bbb;
}

.project-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 20px auto;
    border-radius: 8px;
}

.video-container {
    text-align: center;
    margin: 20px 0;
}

embed {
    display: block;
    margin: 20px auto;
    border: 1px solid #ccc;
    border-radius: 8px;
}
</style>
