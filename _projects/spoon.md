---
title: "Spoon for Arthrogryposis"
date: Aug 2021
category: "professional"
priority: 3
header_image: "/assets/images/IMG_0433.jpeg"
description: "A custom-designed spoon for individuals with Arthrogryposis, enhancing ease of use."
layout: "project"
technologies:
  - CAD Modeling
  - Prototyping
---

<!-- Project Metadata -->
<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} - Oct 2021</span>
</div>

## **Project Overview**
- Researched **Arthrogryposis** and the motor limitations of the disability.
- Developed **screening and scoring matrices** to select the optimal spoon design.
- Iterated through **multiple design concepts** to arrive at a functional final product.
- Produced a **video** documenting the design ideation and iteration process, demonstrating how the product functions.

---
<div class="image-container">
    <img src="/assets/images/IMG_0433.jpeg" alt="Spoon for Arthrogryposis" class="project-image expandable-image" onclick="toggleImageSize(this)">
</div>

---

## **Project Video**
<div style="text-align: center;">
  <iframe width=100%
          src="https://www.youtube.com/embed/0wa5HLWD5Lg" 
          title="Spoon for Arthrogryposis - Demonstration"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
  </iframe>
</div>

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

* Make poster and video match section width */
.image-container {
    max-width: 100%;
    text-align: center;
}

.project-image{
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
