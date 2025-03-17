---
layout: default
title: "Reel"
permalink: /reel/
css_class: "film-page"
---

<!-- Reel Header in the Top Corner -->
<div class="reel-header">
  <h2>Reel</h2>
</div>

<!-- Video Container for Embedded YouTube Video -->
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/pbt21FiMVrA"
          title="Reel Video" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>

<!-- Inline CSS -->
<style>
  /* Reel Header positioned in the top left corner */
  .reel-header {
    position: absolute;
    top: 10px;
    left: 10px;
    font-family: 'Poppins', sans-serif;
    font-size: 1.5rem;
    color: #fff; /* Adjust based on your background */
    z-index: 10;
  }

  /* Video container: full width, with a 16:9 aspect ratio */
  .video-container {
    position: relative;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
    padding-top: 56.25%;  /* 16:9 aspect ratio */
  }
  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
  }

  /* Optional: Set a background color for the page */
  body {
    background-color: #000;  /* or adjust as desired */
  }
</style>
