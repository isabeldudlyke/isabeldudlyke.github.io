---
title: "PARKLIFE"
layout: default
description: "A multi-media 2D animation music video to the song 'Parklife' by Blue"
category: "professional" # Options: "professional" or "personal"
priority: 2
status: "new" # Options: "new", "under_construction"
header_image: "/assets/images/ParkLife2.png"
images:
  - "/assets/images/ParkLife5.png"
  - "/assets/images/ParkLife2.png"
  - "/assets/images/ParkLife1.png"
roles: "DIRECTOR, ANIMATOR, EDITOR"
---

<div class="banner">
  <div class="banner-content">
    <h1>PARKLIFE</h1>
    <a href="/film/" class="back-button">← Back to Films</a>
  </div>
</div>

<div class="film-detail-container">
  <!-- Role, Genre, and Summary -->
  <div class="film-info">
    <div class="film-role-genre">
      <p><strong>Role:</strong></p>
      <p>Director, Animator, Editor</p>
      <p><strong>Genre:</strong></p>
      <p>2D Animation, Experimental, Multi-Media</p>
    </div>
    <div class="film-summary">
      <p><strong>Summary:</strong></p>
      <p>A multi-media 2D animation to the song "Parklife" by Blur. The music video channels the essence of the song in both style and subject, offering an exciting and fast-paced visual experience.</p>
      <p>  Nominated by faculty recommendation for the 2025 Cinematic Arts Awards. </p>

    </div>
  </div>

  <!-- Embedded Video -->
  <div class="film-video">
    <iframe
      width="95%" 
      height="500" 
      src="https://www.youtube.com/embed/9fZRrebTi0A" 
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
  background-image: url('/assets/images/parklife-header.jpg');
  background-size: cover;
  background-position: center;
  height: 300px;
  width: 100vw;
  margin-left: calc(-50vw + 50%);
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
  border-radius: 8px;
  max-width: 1200px;
}
</style>
