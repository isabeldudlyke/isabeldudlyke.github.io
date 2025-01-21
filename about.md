---
layout: default
title: "About"
permalink: /about/
css_class: "about-page"
---

<div class="about-wrapper">
  <!-- About Section -->
  <div class="about-content">
    <h1>Hi, I'm Isabel.</h1>
    <p>
      I am currently a student at Duke University majoring in Mechanical Engineering and Cinematic Arts. 
      I am a proud member of esteemed engineering societies, including Tau Beta Pi, Pi Tau Sigma, which 
      have further fueled my passion for innovation and design. Additionally, I am an active member of 
      Freewater Productions, Duke’s student-run independent film production company, and two theater 
      groups, Duke Players and Hoof ‘n’ Horn, where I frequently take on technical roles in productions. 
      My short film <i>Inner Demons</i> was selected for Duke’s Fall Film Festival following faculty nomination, 
      and I was honored to receive the Robert E. Pristo Filmmaking Award for my current capstone project.
    </p>
    <p>
      I thrive in dynamic, fast-paced environments that demand both creative problem-solving and technical precision. 
      Whether crafting an engineering prototype or leading a film project, I bridge design and execution effectively. 
      With a passion for blending technical expertise and artistic vision, I bring a unique perspective to every challenge, 
      delivering impactful and practical solutions.
    </p>
  </div>

  <!-- Education Section -->
  <div class="resume-section">
    <h2>Education</h2>
    <div class="resume-item">
      <div class="item-title">
        Duke University
        <span class="item-date">Aug 2021 - Present</span>
      </div>
      <div class="item-subtitle">B.S. in Mechanical Engineering, Cinematic Arts</div>
    </div>

    <!-- Professional Experience Section -->
    <h2>Professional Experience</h2>
    <div class="resume-item">
      <div class="item-title">
        Engineering Intern
        <span class="item-date">May 2023 - Aug 2023</span>
      </div>
      <ul class="item-details">
        <li>Designed and implemented CAD models for new product prototypes.</li>
        <li>Collaborated with the R&D team to test and evaluate design performance.</li>
      </ul>
    </div>
  </div>

  <!-- Skills Section -->
  <h2>Skills & Proficiencies</h2>
  <div class="skills-grid">
    <div class="skill-item">
      <img src="assets/images/python.png" alt="Python" />
      <span>Python</span>
    </div>
    <div class="skill-item">
      <img src="assets/images/matlab.png" alt="MATLAB" />
      <span>MATLAB</span>
    </div>
    <div class="skill-item">
      <img src="assets/images/solidworks.png" alt="SolidWorks" />
      <span>SolidWorks</span>
    </div>
  </div>

  <!-- Extracurricular Section -->
  <h2>Extracurricular Activities</h2>
  <div class="extracurricular">
    <div class="activity-row">
      <img src="assets/images/freewater.png" alt="Freewater Productions" class="activity-image" />
      <div class="activity-details">
        <div class="activity-title">Freewater Productions</div>
        <p>Collaborated on student-led film projects, contributing as a cinematographer and editor.</p>
      </div>
    </div>
    <div class="activity-row">
      <img src="assets/images/hoofnhorn.png" alt="Hoof 'n' Horn" class="activity-image" />
      <div class="activity-details">
        <div class="activity-title">Hoof 'n' Horn</div>
        <p>Served as a technical lead, managing lighting and set design for theater productions.</p>
      </div>
    </div>
  </div>
</div>

<style>
/* General Styling */
.about-wrapper {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem 1rem;
  font-family: 'Poppins', sans-serif;
  line-height: 1.6;
  color: #ccc;
}

.about-content h1 {
  font-size: 2.5rem;
  color: white;
  text-align: center;
}

.about-content p {
  font-size: 1rem;
  color: #aaa;
  text-align: center;
  margin-bottom: 2rem;
}

/* Resume Section */
.resume-section {
  margin-top: 2rem;
}

.resume-section h2 {
  font-size: 1.5rem;
  color: white;
  margin-bottom: 1rem;
  text-align: left;
}

.resume-item {
  margin-bottom: 1rem;
}

.item-title {
  display: flex;
  justify-content: space-between;
  font-size: 1.1rem;
  color: #ddd;
  font-weight: 600;
}

.item-subtitle {
  font-size: 1rem;
  color: #aaa;
  margin-top: 0.5rem;
}

.item-details {
  margin-top: 0.5rem;
  padding-left: 1.2rem;
}

.item-details li {
  font-size: 0.9rem;
  color: #ccc;
  list-style: circle;
  margin-bottom: 0.5rem;
}

/* Skills Section */
.skills-grid {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-top: 1.5rem;
}

.skill-item {
  text-align: center;
}

.skill-item img {
  width: 50px;
  height: 50px;
  margin-bottom: 0.5rem;
}

.skill-item span {
  font-size: 0.9rem;
  color: #ccc;
}

/* Extracurricular Section */
.extracurricular {
  margin-top: 2rem;
}

.activity-row {
  display: flex;
  align-items: center;
  margin-bottom: 1.5rem;
}

.activity-image {
  width: 80px;
  height: 80px;
  margin-right: 1rem;
  border-radius: 8px;
}

.activity-details {
  flex: 1;
}

.activity-title {
  font-size: 1.1rem;
  color: #ddd;
  font-weight: 600;
}

.activity-details p {
  font-size: 0.9rem;
  color: #aaa;
}
</style>
