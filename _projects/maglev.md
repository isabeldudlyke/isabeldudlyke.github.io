---
title: "Magnetic Levitation Control System"
date: April 2024
category: "professional"
priority: 3
header_image: "/assets/images/maglev.png"  # Replace with your actual image file
description: "A magnetic levitation system using a PID controller to stably levitate a metal ball."
layout: "project"
technologies:
  - PID Control
  - Control Engineering
  - Electromagnetics
  - Experimental Design
---
<div class="project-meta">
  <span class="project-date">{{ page.date | date: "%b %Y" }}</span>
</div>

## Project Overview
- Developed a magnetic levitation system using a PID controller to stably levitate a metal ball.
- Designed and tuned the system through extensive experimentation and analysis.
- Achieved precise height control through sensor feedback and controller adjustments.

---

<!-- Project Video -->
<div class="video-container">
  <video width="640" height="360" controls>
    <source src="https://raw.githubusercontent.com/isabeldudlyke/isabeldudlyke.github.io/main/assets/videos/maglev.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

---

## **Project Documentation**
<embed src="/assets/documents/maglev.pdf" width="100%" height="600px" type="application/pdf">

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

/* Project Image */
.project-image {
  display: block;
  max-width: 100%;
  width: 100%;
  height: auto;
  margin: 20px auto;
  border-radius: 8px;
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

/* Embedded PDF styling */
embed {
  display: block;
  margin: 20px auto;
  border: 1px solid #ccc;
  border-radius: 8px;
}
</style>
