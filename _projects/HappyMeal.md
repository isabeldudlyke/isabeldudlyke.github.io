---
title: "Happy Meal Ball Maze Toy"
date: Feb 2022
category: "Professional"  
priority: 3
header_image: "/assets/images/Toy.png"  
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
- Developed a **cost-effective** design with **ABS plastic** to ensure durability and safety.
- Implemented **injection molding manufacturing** with an estimated cost of **$0.38 per toy**.
- Conducted **user testing** and improved friction-fit tolerances for an optimal user experience.

---

## **Technical Drawings & Prototyping**
<div class="carousel-container">
    <button class="carousel-btn prev" onclick="changeSlide(-1)">❮</button>
    <div class="carousel">
        <img src="/assets/images/Toy.png" alt="Final Happy Meal Toys" class="carousel-image active expandable-image" onclick="toggleImageSize(this)">
        <img src="/assets/images/TechSketch.png" alt="Technical Drawing" class="carousel-image expandable-image" onclick="toggleImageSize(this)">
        <img src="/assets/images/ExplodedView.png" alt="Exploded View" class="carousel-image expandable-image" onclick="toggleImageSize(this)">
    </div>
    <button class="carousel-btn next" onclick="changeSlide(1)">❯</button>
</div>

---

## **Project Documentation**
<embed src="/assets/documents/HappyMeals.pdf" width="100%" height="600px" type="application/pdf">
<p style="text-align: center;">
View the full **project report** above or <a href="/assets/documents/HappyMeals.pdf" target="_blank">download it here</a>.
</p>

---

## **Cost Analysis**
- **Manufacturing Cost:** The total cost per unit was estimated at **$0.38** using **injection molding**.
- **Material Costs:** ABS plastic was selected for its **durability, low cost, and recyclability**.
- **Production Feasibility:** The mold was designed for **high-volume manufacturing**, reducing per-unit costs as production scales.

## **Marketing Analysis**
- **Target Audience:** Children ages **3-10**, incorporating **popular themes (Encanto, Cars, Lightyear)**.
- **Brand Alignment:** The design integrates with **McDonald's existing Happy Meal branding**, enhancing collectibility.
- **Sustainability Considerations:** The toy is designed for **recyclability and minimal material waste**, aligning with sustainability goals.

## **Project Results & Key Findings**
- **User Testing:** Positive feedback was received on **ease of use and durability**.
- **Manufacturability Success:** The toy was successfully **manufactured using injection molding**, demonstrating feasibility.
- **Improvements:** Adjustments to **snap-fit tolerances and friction joints** improved the final design's assembly quality.

---

<style>
/* General Styles */
.project-content h1 {
    color: #f0f0f0;
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

/* Carousel Container */
.carousel-container {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    max-width: 800px;
    margin: auto;
    position: relative;
}

/* Image Carousel */
.carousel {
    display: flex;
    overflow: hidden;
    width: 100%;
    justify-content: center;
    align-items: center;
    position: relative;
}
.carousel-image {
    display: none;
    width: 100%;
    max-width: 700px;
    height: auto;
    border-radius: 8px;
    transition: transform 0.3s ease;
}
.carousel-image.active {
    display: block;
}

/* Navigation Buttons */
.carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0,0,0,0.5);
    color: white;
    border: none;
    cursor: pointer;
    padding: 10px;
    font-size: 2rem;
    border-radius: 50%;
}
.prev { left: -40px; }
.next { right: -40px; }
.carousel-btn:hover {
    background-color: rgba(0,0,0,0.8);
}

/* Click-to-Expand */
.expandable-image {
    cursor: pointer;
}
.expandable-image.expanded {
    transform: translate(-50%, -50%) scale(1.8);
    position: fixed;
    top: 50%;
    left: 50%;
    z-index: 1000;
    background: rgba(0,0,0,0.8);
    padding: 10px;
    border-radius: 8px;
}

/* PDF Styling */
embed {
    display: block;
    margin: 20px auto;
    border: 1px solid #ccc;
    border-radius: 8px;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
    let currentSlide = 0;
    const images = document.querySelectorAll(".carousel-image");

    function showSlide(index) {
        images.forEach((img, i) => {
            if (i === index) {
                img.classList.add("active");
            } else {
                img.classList.remove("active");
            }
        });
    }

    window.changeSlide = function(step) {
        currentSlide += step;
        if (currentSlide >= images.length) currentSlide = 0;
        if (currentSlide < 0) currentSlide = images.length - 1;
        showSlide(currentSlide);
    };

    window.toggleImageSize = function(img) {
        img.classList.toggle("expanded");
    };

    showSlide(currentSlide);
});
</script>
