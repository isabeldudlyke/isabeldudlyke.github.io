---
title: "Optimized Truss Design Using FEA"
date: Feb 2024
category: "personal"  
priority: 3
header_image: "/assets/images/Truss.png" 
description: "A robust and efficient truss-based stand designed for industrial fluid systems, validated using FEA."
layout: "project"  
technologies:
  - SolidWorks
  - FEA Analysis
  - Mechanical Design
  - Material Science
---

<div class="project-meta">
    <span class="project-date">{{ page.date | date: "%b %Y" }}</span>
</div>

## Project Overview
- Designed a truss-based stand to support industrial fluid systems under strict safety and weight requirements.
- Iteratively refined the design using SolidWorks and FEA, achieving a final efficiency score of 74.569.
- The final design supports 30 times its own mass, meeting all criteria with a minimum factor of safety of 3.7.

---

## Design Process

I conducted multiple design iterations to optimize the truss geometry. The initial design revealed high stress in the vertical members, so I removed them to distribute loads more evenly. Subsequent iterations introduced a triangular configuration that improved efficiency and reduced weight. FEA simulations confirmed that the final design, constructed from 2024 Aluminum Alloy, meets the load-bearing requirements and achieves a maximum supported load of 430,000 lbf.

---

<img src="/assets/images/Truss.png" alt="Truss" class="project-image" />

---

## **Project Documentation**
<embed src="/assets/documents/truss.pdf" width="100%" height="600px" type="application/pdf">

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
