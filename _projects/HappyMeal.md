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
- Developed a **cost-effective** design with **ABS plastic** to ensure durability and safety.
- Implemented **injection molding manufacturing** with an estimated cost of **$0.38 per toy**.
- Conducted **user testing** and improved friction-fit tolerances for an optimal user experience.

---

## **Technical Drawings & Prototyping**
### **Technical Sketch**
<img src="/assets/images/TechSketch.png" alt="Technical Drawing" class="project-image expandable-image" onclick="toggleImageSize(this)">

### **Exploded View**
<img src="/assets/images/ExplodedView.png" alt="Exploded View" class="project-image expandable-image" onclick="toggleImageSize(this)">

### **Final Toy Designs**
<img src="/assets/images/Toy.png" alt="Final Happy Meal Toys" class="project-image expandable-image" onclick="toggleImageSize(this)">

---

## **Project Documentation**
<embed src="/assets/documents/HappyMeals.pdf" width="100%" height="600px" type="application/pdf">

---

<div class="text-content">
    <h2>Cost Analysis</h2>
    <ul>
        <li><strong>Manufacturing Cost:</strong> The total cost per unit was estimated at <strong>$0.38</strong> using injection molding.</li>
        <li><strong>Material Costs:</strong> ABS plastic was selected for its <strong>durability, low cost, and recyclability</strong>.</li>
        <li><strong>Production Feasibility:</strong> The mold was designed for <strong>high-volume manufacturing</strong>, reducing per-unit costs as production scales.</li>
    </ul>

    <h2>Marketing Analysis</h2>
    <ul>
        <li><strong>Target Audience:</strong> Children ages <strong>3-10</strong>, incorporating popular themes (<em>Encanto, Cars, Lightyear</em>).</li>
        <li><strong>Brand Alignment:</strong> The design integrates with <strong>McDonald's existing Happy Meal branding</strong>, enhancing collectibility.</li>
        <li><strong>Sustainability Considerations:</strong> The toy is designed for <strong>recyclability and minimal material waste</strong>, aligning with sustainability goals.</li>
    </ul>

    <h2>Project Results & Key Findings</h2>
    <ul>
        <li><strong>User Testing:</strong> Positive feedback was received on <strong>ease of use and durability</strong>.</li>
        <li><strong>Manufacturability Success:</strong> The toy was successfully <strong>manufactured using injection molding</strong>, demonstrating feasibility.</li>
        <li><strong>Improvements:</strong> Adjustments to <strong>snap-fit tolerances and friction joints</strong> improved the final design's assembly quality.</li>
    </ul>
</div>

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

/* Main image styling */
.project-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 20px auto;
    border-radius: 8px;
    cursor: pointer;
    transition: transform 0.3s ease;
}

/* Click to expand */
.project-image.expanded {
    transform: scale(1.8);
    cursor: zoom-out;
}

/* Small images layout */
.image-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    flex-wrap: wrap;
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
function toggleImageSize(img) {
    img.classList.toggle("expanded");
}
</script>
