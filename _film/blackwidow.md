---
title: "BLACK WIDOW"
layout: default
description: "An experimental feminist short using recycled cinema to explore patriarchy and the lives of women"
category: "professional" # Options: "professional" or "personal"
priority: 6
status: "new" # Options: "new", "under_construction"
header_image: "/assets/images/BlackWidow1.png"
images:
  - "/assets/images/BlackWidow2.png"
  - "/assets/images/BlackWidow1.png"
  - "/assets/images/BlackWidow3.png"
roles: "EDITOR"
---

<div class="banner">
  <div class="banner-content">
    <h1>BLACK WIDOW</h1>
    <a href="/film/" class="back-button">← Back to Films</a>
  </div>
</div>

<div class="film-detail-container">
  <!-- Role, Genre, and Summary -->
  <div class="film-info">
    <div class="film-role-genre">
      <p><strong>Role:</strong></p>
      <p>Editor</p>
      <p><strong>Genre:</strong></p>
      <p>Experimental, Recycled Cinema, Feminist</p>
    </div>
    <div class="film-summary">
      <p><strong>Summary:</strong></p>
      <p>An experimental feminist short film dissecting the lives of women in the modern world and patriarchy. Crafted using recycled cinematic material, the piece challenges visual narratives through bold juxtapositions and layered meaning.</p>
    </div>
  </div>

  <!-- Embedded Video -->
  <div class="film-video">
    <iframe
      width="95%" 
      height="500" 
      src="https://www.youtube.com/embed/cFGPPTc37xs" 
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
  background-image: url('/assets/images/BlackWidow1.png');
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

.film
