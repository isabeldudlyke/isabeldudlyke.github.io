---
layout: default
title: "Reel"
permalink: /reel/
css_class: "reel-page"
---

<!-- Reel Header in the Top Corner -->
# Reel

---

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
  .reel-page h1 {
    font-size: 2rem; /* Adjust this value for the desired size */
    margin-bottom: 1rem; /* Optional: Adjust spacing below the title */
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

</style>
