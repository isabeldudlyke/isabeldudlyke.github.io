---
title: "ÉLIPHAS"
layout: default
description: "Alone in a barn at night, a girl prepares a satanic ritual with a goat’s blood—unaware something ancient is watching."
category: "professional" # Options: "professional" or "personal"
priority: 1
status: "new" # Options: "new", "under_construction"
header_image: "/assets/images/Ondine_1.16.1.jpg"
images:
  - "/assets/images/GoatEye_1.4.1.jpg"
  - "/assets/images/Ondine_1.16.1.jpg"
  - "/assets/images/GoatMouth_1.3.2.jpg"
roles: "DIRECTOR, WRITER, PRODUCER, EDITOR"
---

<div class="banner">
  <div class="banner-content">
    <h1>ÉLIPHAS</h1>
    <a href="/film/" class="back-button">← Back to Films</a>
  </div>
</div>

<div class="film-detail-container">
  <!-- Role, Genre, and Summary -->
  <div class="film-info">
    <div class="film-role-genre">
      <p><strong>Role:</strong></p>
      <p>Director, Producer, Writer, Editor</p>
      <p><strong>Genre:</strong></p>
      <p>Horror, Comedy, Short</p>
    </div>
    <div class="film-summary">
      <p><strong>Summary:</strong></p>
      <p>Alone in a barn at night, a girl prepares a satanic ritual with a goat’s blood—unaware something ancient is watching. Created for my Senior capstone in Cinematic Arts. </p>
      <p>Funded by the Robert E. Pristo Filmmaking Award and the Creative Arts Award.</p>
    </div>
  </div>

  <!-- Embedded Video -->
  <div class="film-video">
    <iframe
      width="95%" 
      height="500" 
      src="https://www.youtube.com/embed/EZu0iwTgTKc" 
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
      allowfullscreen>
    </iframe>
  </div>
</div>

<style>
/* Banner Section */
.banner {
  background-image: url('/assets/images/Ondine_1.16.1.jpg');
  background-size: cover;
  background-position: center;
  height: 300px; /* Adjust the height as needed */
  width: 100vw; /* Use viewport width to span the screen */
  margin-left: calc(-50vw + 50%); /* Negate container constraints */
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.banner-content {
  text-align: center;
  color: white;
  text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6);
}

.banner h1 {
  font-size: 4rem;
  margin: 0;
}

.back-button {
  position: absolute;
  top: 20px;
  left: 20px;
  color: white;
  text-decoration: none;
  font-size: 1rem;
  background: rgba(0, 0, 0, 0.5);
  padding: 0.5rem 1rem;
  border-radius: 4px;
}

/* Film Info Section */
.film-detail-container {
  width: 90%;
  max-width: 1200px;
  margin: 2rem auto;
  font-family: 'Poppins', sans-serif;
  color: #ccc;
  line-height: 1.6;
}

.film-info {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  margin-bottom: 2rem;
}

.film-role-genre {
  flex: 1;
}

.film-role-genre p {
  margin: 0.5rem 0;
  font-size: 1rem;
}

.film-summary {
  flex: 2;
}

.film-summary p {
  margin: 0;
  font-size: 1rem;
}

/* Embedded Video Section */
.film-video {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}

.film-video iframe {
  border-radius: 8px; /* Optional: rounded corners */
  max-width: 1200px; /* Cap the maximum width */
}
</style>
