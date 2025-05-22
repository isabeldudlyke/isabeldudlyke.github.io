---
title: "Rainbow Road Rage – Kinetic Sculpture Race"
date: May 2025
category: "professional"
priority: 1
header_image: "/assets/images/KineticSculpture.jpeg"  # Replace with actual image
description: "A Mario Kart–themed amphibious sculpture built for the 2025 Baltimore Kinetic Sculpture Race. Designed for 15 miles across land, water, and sand."
layout: "project"
technologies:
  - CAD & FEA
  - Structural Fabrication
  - Thematic Design
  - Project Management
---

<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} – Apr 2022</span>
</div>

## Project Overview
- Led design and aesthetics for *Rainbow Road Rage*, a Mario Kart–themed amphibious sculpture.
- Fabricated pontoons, structural elements, and a decorative  piranha plant using FEA-informed designs.
- Completed the full 15-mile race across land, water, and sand—earning the **ACE Award**, the top honor for acing every challenge.
- Managed a large-scale team effort spanning mechanical testing, design iteration, and visual storytelling.

See the [official race site](https://kineticbaltimore.com/KSR/2025/?Page=8) for results and photos,  
and check out the [New York Times article](https://www.nytimes.com/card/2025/05/05/arts/baltimore-kinetic-sculpture-race?unlocked_article_code=1.E08.HlXT.7oiIRsKUmh-a&smid=url-share) featuring highlights from the 2025 competition.

---

## Technical Drawings & Prototyping
<div class="carousel-container">
  <button class="carousel-btn prev" onclick="changeSlide(-1)">❮</button>
  <div class="carousel">
    <img src="/assets/images/KineticSculpture.jpeg" alt="Final Sculpture in Race" class="carousel-image active" onclick="toggleImageSize(this)">
    <img src="/assets/images/InRace.HEIC" alt="During Race" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/CAD.png" alt="CAD" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/One Page Info Sheet.png" alt="Info Sheet" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/Pon_Assembly.png" alt="Pontoon Construction" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/Pon_2.jpeg" alt="Pontoon Design" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/PP_1.jpeg" alt="Pirahna Plant 1" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/PP_2.jpeg" alt="Pirahna Plant 2" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/PP_3.jpeg" alt="Pirahna Plant 3" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/PP_4.jpeg" alt="Pirahna Plant 4" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/PP_Stand.png" alt="Pirahna Plant Stand" class="carousel-image" onclick="toggleImageSize(this)">

  </div>
  <button class="carousel-btn next" onclick="changeSlide(1)">❯</button>
</div>

---

## Project Documentation
<embed src="/assets/documents/ME 424 Final Report - Kinetic Sculpture.pdf" width="100%" height="600px" type="application/pdf">


<style>
  
.project-content h1 {
    color: #f0f0f0;  /* Light gray (adjust as needed) */
    font-size: 2.5rem;  /* Adjust for visibility */
    margin-bottom: 10px;
}
/* Project Metadata */
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
/* Carousel Images: set uniform height */
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
