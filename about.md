---
layout: default
title: "About"
permalink: /about/
css_class: "about-page"
---

<div class="about-wrapper">
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

    <!-- Resume Information -->
    <section class="resume-section">
      <h2>Education</h2>
      <div>
        <h3>Duke University</h3>
        <p>Major: Mechanical Engineering and Cinematic Arts</p>
        <p>Aug 2021 - Present</p>
      </div>
    </section>

    <section class="resume-section">
      <h2>Professional Experience</h2>
      <div>
        <h3>Engineering Intern</h3>
        <p>Company Name</p>
        <p>June 2023 - Aug 2023</p>
        <ul>
          <li>Contributed to the design and testing of advanced mechanical systems.</li>
          <li>Collaborated with cross-functional teams to solve engineering challenges.</li>
        </ul>
      </div>
    </section>

    <section class="resume-section">
      <h2>Skills & Proficiencies</h2>
      <div class="skills">
        <div class="skill-item">
          <img src="/path/to/python-icon.png" alt="Python Icon" />
          <p>Python</p>
        </div>
        <div class="skill-item">
          <img src="/path/to/cad-icon.png" alt="CAD Icon" />
          <p>CAD</p>
        </div>
      </div>
    </section>

    <section class="resume-section">
      <h2>Extracurriculars</h2>
      <div class="extracurricular-item">
        <img src="path/to/club-image1.png" alt="Club Logo" />
        <div>
          <h3>Freewater Productions</h3>
          <ul>
            <li>Directed and produced multiple short films.</li>
            <li>Collaborated with a team of students on film editing and production.</li>
          </ul>
        </div>
      </div>
      <div class="extracurricular-item reverse">
        <img src="path/to/club-image2.png" alt="Club Logo" />
        <div>
          <h3>Duke Players</h3>
          <ul>
            <li>Technical support for theatrical productions.</li>
            <li>Managed stage lighting and sound engineering.</li>
          </ul>
        </div>
      </div>
    </section>
  </div>
</div>

<style>
  /* Center the text and reduce font size */
  .about-wrapper {
    text-align: center;
    padding: 2rem;
    font-family: 'Poppins', sans-serif;
  }

  .about-content {
    max-width: 800px;
    margin: 0 auto;
    color: #333;
    font-size: 1rem; /* Slightly smaller font */
  }

  .resume-section {
    margin-top: 2rem;
    text-align: left;
  }

  .resume-section h2 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }

  .skills {
    display: flex;
    justify-content: center;
    gap: 1rem;
    flex-wrap: wrap;
  }

  .skill-item {
    text-align: center;
    width: 100px;
  }

  .skill-item img {
    width: 50px;
    height: 50px;
  }

  .extracurricular-item {
    display: flex;
    align-items: center;
    margin-bottom: 2rem;
  }

  .extracurricular-item img {
    width: 100px;
    height: 100px;
    margin-right: 1rem;
  }

  .extracurricular-item.reverse {
    flex-direction: row-reverse;
  }

  .extracurricular-item.reverse img {
    margin-right: 0;
    margin-left: 1rem;
  }
</style>
