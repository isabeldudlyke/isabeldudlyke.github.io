---
title: "Candyland Castle Sportbot"
date: Mar 2022
category: "professional"
priority: 3
header_image: "/assets/images/DC6 Photo.png"  # Update with your actual image file
description: "A Candyland-themed Sportbot, a key component of our Rube-Goldberg machine featuring a rising drawbridge and dynamic LED effects."
layout: "project"
technologies:
  - Circuit Design
  - Mechanical Integration
  - Arduino Programming
  - Rapid Prototyping
---

<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} – Apr 2022</span>
</div>

## Project Overview
- Developed the Candyland Castle Sportbot as a crucial part of our Rube‑Goldberg machine.
- Designed a rising drawbridge mechanism actuated by a push-button and 555 timer circuit.
- Integrated Arduino-controlled LEDs to create dynamic lighting effects.
- Achieved a reliable and repeatable operation that enhances the overall Candyland theme.

---

## Technical Drawings & Prototyping
<div class="carousel-container">
  <button class="carousel-btn prev" onclick="changeSlide(-1)">❮</button>
  <div class="carousel">
    <img src="/assets/images/DC6 Photo.png" alt="Sportbot Prototype 1" class="carousel-image active" onclick="toggleImageSize(this)">
    <img src="/assets/images/circuit 1.png" alt="Sportbot Prototype 2" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/circuit 2.png" alt="Sportbot Prototype 3" class="carousel-image" onclick="toggleImageSize(this)">
    <img src="/assets/images/schematic.png" alt="Sportbot Prototype 4" class="carousel-image" onclick="toggleImageSize(this)">
  </div>
  <button class="carousel-btn next" onclick="changeSlide(1)">❯</button>
</div>

---

## Project Documentation
<embed src="/assets/documents/DC 6.pdf" width="100%" height="600px" type="application/pdf">

---
## Demo Video

<div class="video-container">
    <video width="640" height="480" controls>
        <source src="https://raw.githubusercontent.com/isabeldudlyke/isabeldudlyke.github.io/main/assets/videos/SportBot.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

In this video, all the sportbots from each group were combined to create a much larger Rube-Goldberg Machine. Our sportbot was the first in the chain and you can see the ball triggering the button causing the drawbridge to lift and send the ball rolling through the candyland castle into the next sportbot. 

---

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
