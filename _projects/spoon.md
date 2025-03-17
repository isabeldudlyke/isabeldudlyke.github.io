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

<!-- Project Image -->
<div class="image-container">
  <img src="/assets/images/IMG_0433.jpeg" alt="Spoon for Arthrogryposis" class="project-image">
</div>

---

<!-- Project Video -->
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/0wa5HLWD5Lg" 
          title="Spoon for Arthrogryposis - Demonstration" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>

---

<!-- Inline CSS for Responsive Image & Video -->
<style>
.project-content h1 {
    color: #f0f0f0;  /* Light gray (adjust as needed) */
    font-size: 2.5rem;  /* Adjust for visibility */
    margin-bottom: 10px;
}
/* Project Metadata */
.project-meta {
  font-size: 0.9rem;
  color: #666;
  margin-bottom: 1.5rem;
  font-family: var(--body-font);
}
.project-date {
  display: block;
  font-size: 1rem;
  color: #bbb;
}

/* Image Container */
.image-container {
  width: 100%;
  max-width: 1000px;
  margin: 20px auto;
  text-align: center;
}

/* Project Image: Make it the same width as the video */
.project-image {
  display: block;
  width: 100%;
  max-width: 1000px;
  height: auto;
  border-radius: 8px;
  margin: 20px auto;
  /* No click-to-expand functionality */
}

/* Video Container: Using aspect-ratio trick for 16:9 ratio */
.video-container {
  position: relative;
  width: 100%;
  max-width: 1000px;
  margin: 20px auto;
  padding-top: 56.25%;  /* 16:9 ratio */
}
.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}
</style>
