---
title: "Happy Meal Ball Maze Toy"
date: Feb 2022
category: "Professional"  
priority: 3
header_image: "/assets/images/Toy.png"  # Update with actual image file
description: "A fun, cost-efficient, and sustainable Happy Meal toy designed for mass production."
layout: "project"  
technologies:
  - SolidWorks
  - Injection Molding
  - Rapid Prototyping
  - Design for Manufacturability
---

<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} - March 2022</span>
</div>

## **Project Overview**
- Designed a **puzzle maze toy** with interchangeable backgrounds for **Happy Meals**.
- Used **SolidWorks** for CAD modeling and **tolerance analysis** for manufacturability.
- Developed a **cost‑effective** design with **ABS plastic** to ensure durability and safety.
- Implemented **injection molding manufacturing** with an estimated cost of **$0.38 per toy**.
- Conducted **user testing** and improved friction‑fit tolerances for an optimal user experience.

---

## **Technical Drawings & Prototyping**
<div class="carousel-container">
  <button class="carousel-btn prev" onclick="changeSlide(-1)">❮</button>
  <div class="carousel">
    <img src="/assets/images/Toy.png" alt="Final Happy Meal Toys" class="carousel-image active" onclick="toggleImageSize(this)">
    <img src="/assets/images/TechSketch.png" alt="Technical Drawing" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/ExplodedView.png" alt="Exploded View" class="carousel-image" onclick="toggleImageSize(this)">
  </div>
  <button class="carousel-btn next" onclick="changeSlide(1)">❯</button>
</div>

---

## **Project Documentation**
<embed src="/assets/documents/HappyMeals.pdf" width="100%" height="600px" type="application/pdf">

---

## **Cost Analysis**
- **Manufacturing Cost:** The total cost per unit was estimated at **$0.38** using **injection molding**.
- **Material Costs:** ABS plastic was selected for its **durability, low cost, and recyclability**.
- **Production Feasibility:** The mold was designed for **high‑volume manufacturing**, reducing per‑unit costs as production scales.

## **Marketing Analysis**
- **Target Audience:** Children ages **3‑10**, incorporating **popular themes (Encanto, Cars, Lightyear)**.
- **Brand Alignment:** The design integrates with **McDonald's existing Happy Meal branding**, enhancing collectibility.
- **Sustainability Considerations:** The toy is designed for **recyclability and minimal material waste**, aligning with sustainability goals.

## **Project Results & Key Findings**
- **User Testing:** Positive feedback was received on **ease of use and durability**.
- **Manufacturability Success:** The toy was successfully **manufactured using injection molding**, demonstrating feasibility.
- **Improvements:** Adjustments to **snap‑fit tolerances and friction joints** improved the final design's assembly quality.

---

<!-- Inline CSS for Carousel -->
<style>
  /* Carousel Container */
  .carousel-container {
    position: relative;
    width: 100%;
    max-width: 700px;
    margin: 20px auto;
    overflow: hidden;
    text-align: center;
  }
  /* Carousel: images will be stacked vertically, but only one is shown */
  .carousel {
    width: 100%;
  }
  /* Carousel images: override global styles with a more specific selector */
  .carousel-container .carousel-image {
    width: 100%;
    max-width: 700px;
    display: none;
    border-radius: 8px;
    cursor: pointer;
    margin: 0 auto;
  }
  .carousel-container .carousel-image.active {
    display: block;
  }
  /* Navigation Buttons */
  .carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0,0,0,0.5);
    color: #fff;
    border: none;
    font-size: 2rem;
    padding: 0.5rem 1rem;
    cursor: pointer;
    z-index: 10;
  }
  .carousel-btn.prev {
    left: 10px;
  }
  .carousel-btn.next {
    right: 10px;
  }
  .carousel-btn:hover {
    background-color: rgba(0,0,0,0.8);
  }
  /* Click-to-Expand: limit expanded size */
  .carousel-container .carousel-image.expanded {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    max-width: 90vw;
    max-height: 90vh;
    z-index: 1000;
    background: rgba(0,0,0,0.8);
    padding: 10px;
    border-radius: 8px;
  }
</style>

<!-- Inline JavaScript for Carousel Functionality -->
<script>
document.addEventListener("DOMContentLoaded", function() {
  const images = document.querySelectorAll('.carousel-container .carousel-image');
  let currentSlide = 0;
  function showSlide(index) {
    images.forEach((img, i) => {
      img.classList.toggle('active', i === index);
    });
  }
  window.changeSlide = function(step) {
    currentSlide += step;
    if (currentSlide >= images.length) currentSlide = 0;
    if (currentSlide < 0) currentSlide = images.length - 1;
    showSlide(currentSlide);
  }
  window.toggleImageSize = function(img) {
    img.classList.toggle('expanded');
  }
  showSlide(currentSlide);
});
</script>
