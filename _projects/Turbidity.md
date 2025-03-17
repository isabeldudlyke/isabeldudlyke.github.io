---
title: "Turbidity Meter"
date: Sep 2021
category: "professional"
priority: 3
header_image: "/assets/images/TribidityPoster_edited_edited.jpg"
description: "A cost-effective device to measure water turbidity."
layout: "project"
technologies:
  - 3D Printing
  - Microcontrollers
  - Sensor Calibration
  - Circuit Design
---

<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }} - Dec 2021 </span>
</div>

## **Project Overview**
- Researched extensively into available designs and technologies for measuring water turbidity.
- Developed a functional and **cost-effective design** for measuring the turbidity of water samples.
- Created the **circuit and code** to measure and display turbidity values.
- **3D printed** an enclosure to house the device.
- **Successfully pitched and presented** the device to the client.

---

## **Project Poster**
<div class="image-container">
    <img src="/assets/images/TribidityPoster.jpg" alt="Turbidity Meter Poster" class="project-image expandable-image" onclick="toggleImageSize(this)">
</div>

---

## **Key Achievements**
- **Designed and developed** a functional water turbidity meter.
- **Reduced costs by 80%** compared to existing commercial designs.
- **Improved reliability** through rigorous testing and sensor calibration.

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
