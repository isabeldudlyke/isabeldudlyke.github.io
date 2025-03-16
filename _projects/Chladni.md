---
title: "Modelling the Chladni Effect"
date: July 2023
category: "Professional"  
priority: 3
header_image: "/assets/images/ChaldniPoster_edited.jpg" 
description: "Modelling the Chladni Effect using Partial Differential Equations"
layout: "project"  
technologies:
  - MATLAB
  - Partial Differential Equations
  - Numerical Simulation
  - Physics-based Modeling
---

<div class="project-meta">
    <span class="project-date">{{ page.date | date: "%b %Y" }} - Aug 2023</span>
</div>

## **Project Overview**
- Modeled **Chladni plate vibrations** using the **2D wave equation**.
- Used **analytical and numerical methods** to solve the PDEs for standing wave solutions.
- Simulated **sand particle motion** to visualize **nodal and anti-nodal patterns**.
- Implemented **MATLAB simulations** and compared theoretical vs. experimental results.

---

## **Poster Presentation**
<div class="image-container">
    <img src="/assets/images/ChaldniPoster.jpg" alt="Chladni Effect Poster" class="project-image expandable-image" onclick="toggleImageSize(this)">
</div>

---

## **Simulation Video**
<div class="video-container">
    <video class="wide-video" autoplay loop muted playsinline>
        <source src="https://raw.githubusercontent.com/isabeldudlyke/isabeldudlyke.github.io/main/assets/videos/Simulation.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

---

## **Simulation Results**
- The 2D **wave equation solutions** provided accurate predictions of Chladni pattern formations.
- **3D wave functions** were plotted to visualize **standing wave behavior** on the plate.
- A **particle-based simulation** modeled sand movement, confirming theoretical predictions.

---

<script>
function toggleImageSize(img) {
    img.classList.toggle("expanded");
}
</script>

---

<style>

.project-content h1 {
    color: #f0f0f0;  /* Light gray */
    font-size: 2.5rem;
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

/* Make poster and video match section width */
.image-container, .video-container {
    max-width: 100%;
    text-align: center;
}

.project-image, .wide-video {
    width: 100%;  /* Make image and video as wide as section dividers */
    max-width: 900px; /* Limit size on larger screens */
    height: auto;
    margin: 20px auto;
    border-radius: 8px;
    cursor: pointer;
    transition: transform 0.3s ease;
}

/* Click to expand the image */
.project-image.expanded {
    transform: scale(1.8); /* Expand image */
    cursor: zoom-out;
}

/* Limit max expansion to avoid overflow */
@media (max-width: 768px) {
    .project-image.expanded {
        transform: scale(1.2);
    }
}

embed {
    display: block;
    margin: 20px auto;
    border: 1px solid #ccc;
    border-radius: 8px;
}
</style>
