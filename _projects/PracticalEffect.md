---
title: "Practical Blood Pump Special Effect"
date: Feb 2025
category: "personal"
priority: 3
header_image: "/assets/images/IMG_8066.heic"  # Update with your actual image file
description: "A practical special effect for my Senior Capstone Horror Film, featuring a fake blood pump system."
layout: "project"
technologies:
  - Practical Stage Effects
  - Fabrication
---

<!-- Project Metadata -->
<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }}</span>
</div>

## Project Overview
- Developed and fabricated my own practical effect for my Senior Capstone Horror Film.
- Achieved a cheap yet highly effective and exaggerated fake blood pump system that delivers a heightened, theatrical horror effect.

---

## Project Photo
<div class="image-container">
  <img src="/assets/images/IMG_8066.heic" alt="Practical Blood Pump Setup" class="project-image">
</div>

---

## How I Made It
- **Prosthetic & Tubing:**  
  I used a latex prosthetic with strategically cut holes and attached flat heat shrink tubing (with a side slit) so it could sit flush against the actor’s neck.
- **Sealing & Connection:**  
  I sealed the tubing around the prosthetic with glue and shrunk the tubing section from ~1 inch off the prosthetic to connect it to a large plastic syringe.
- **Operation:**  
  The syringe, loaded with thin fake blood, was pressed during filming to force the liquid through the tubing, out the slit and holes. The prosthetic was attached with Pros-Aide, colored to match the actor’s skin, and accented with thicker fake blood to mask the edges.

---

## Project Video
<div class="video-warning" style="border: 1px solid red; padding: 0.5rem; margin: 1rem 0; color: red; text-align: center;">
  Warning: This video contains simulated blood effects.
</div>

<div class="video-container">
    <video class="wide-video" controls>
        <source src="https://raw.githubusercontent.com/isabeldudlyke/isabeldudlyke.github.io/main/assets/videos/Effect.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

---

<script>
function toggleImageSize(img) {
    img.classList.toggle("expanded");
}
</script>

---

<style>
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

/* Center the image container using flexbox */
.image-container {
    width: 100%;
    max-width: 900px;
    margin: 20px auto;
    display: flex;
    justify-content: center;
}
.project-image {
    width: 100%;
    max-width: 900px;
    height: auto;
    border-radius: 8px;
    cursor: pointer;
    transition: transform 0.3s ease;
    /* Remove any extra margins if necessary */
}

/* Video Container: maintain a 16:9 ratio */
.video-container {
    position: relative;
    width: 100%;
    max-width: 900px;
    margin: 20px auto;
    padding-top: 56.25%;  /* 16:9 aspect ratio */
}
.video-container iframe,
.video-container video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
}

/* Click-to-expand styling (if still enabled) */
.project-image.expanded {
    transform: scale(1.8);
    cursor: zoom-out;
}

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
