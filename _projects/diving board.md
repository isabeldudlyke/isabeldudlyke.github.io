---
title: "Diving Board Load Cell Project"
date: Feb 2024
category: "professional"  
priority: 3
header_image: "/assets/images/DivingBoard.png"  # Update with actual image file
description: "A project to analyze the deflection and load response of a diving board using a load cell to optimize diver performance."
layout: "project"  
technologies:
  - Mechanical Analysis
  - Load Cells
  - FEA
  - Arduino Programming
---

<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} - March 2022</span>
</div>

## **Project Overview**
- Designed and constructed a miniature diving board test stand to evaluate force and deflection under load.
- Integrated a load cell amplifier and Arduino to convert voltage readings into accurate force and strain energy measurements.
- Calibrated the system using known masses and compared theoretical predictions with experimental results.
- Gathered data to help optimize diver performance by correlating load, deflection, and strain energy with the board's behavior.

---

## **Technical Drawings & Prototyping**
<div class="carousel-container">
  <button class="carousel-btn prev" onclick="changeSlide(-1)">❮</button>
  <div class="carousel">
    <img src="/assets/images/DivingBoard.png" alt="Board Prototype" class="carousel-image active" onclick="toggleImageSize(this)">
    <img src="/assets/images/DivingCircuit.png" alt="Circuit Schematic" class="carousel-image" onclick="toggleImageSize(this)">
  </div>
  <button class="carousel-btn next" onclick="changeSlide(1)">❯</button>
</div>

---

## **Project Documentation**
<embed src="/assets/documents/DivingBoard.pdf" width="100%" height="600px" type="application/pdf">

---

<!-- Inline CSS for Carousel -->
<style>
  
.project-content h1 {
    color: #f0f0f0;  /* Light gray (adjust as needed) */
    font-size: 2.5rem;  /* Adjust for visibility */
    margin-bottom: 10px;
}
  /* Carousel Container */
  .carousel-container {
    position: relative;
    width: 100%;
    max-width: 700px;
    margin: 20px auto;
    overflow: hidden;
    text-align: center;
  }
  /* Carousel */
  .carousel {
    width: 100%;
  }
  /* Carousel images: more specific selector; set a uniform height */
  .carousel-container .carousel-image {
    width: 100%;
    max-width: 700px;
    height: 400px; /* Fixed height for uniformity */
    object-fit: contain;
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
    width: auto;
    height: auto;
    z-index: 1000;
    background: rgba(0,0,0,0.8);
    padding: 10px;
    border-radius: 8px;
    object-fit: contain;
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
