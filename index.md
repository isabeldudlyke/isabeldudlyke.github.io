---
layout: default
title: "Home"
css_class: Home
---

<div class="center-wrapper">
  <div class="center-content">
    <h1>Isabel Dudlyke</h1>
    <h2>Filmmaker <span class="dot">•</span> Engineer</h2>
  </div>
</div>

<footer class="footer">
  <p>&copy; 2025 Isabel Dudlyke. All Rights Reserved.</p>
</footer>

<style>
  /* Background setup */
  body {
    background-image: url('tower.jpg'); /* Ensure this file is in the correct path */
    background-size: cover; /* Make the image cover the entire viewport */
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Avoid repeating the image */
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }

  /* Wrapper to handle content and footer positioning */
  .center-wrapper {
    flex: 1; /* Takes up remaining space to push the footer down */
    display: flex;
    justify-content: center;
    align-items: center;
  }

  /* Centered content */
  .center-content {
    text-align: center;
    color: white; /* Ensure text is readable */
    font-family: 'Poppins', sans-serif;
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6); /* Subtle shadow for readability */
  }

  .center-content h1 {
    font-size: 4rem; /* Larger font for the main title */
    margin: 0;
  }

  .center-content h2 {
    font-size: 1.5rem; /* Smaller font for the subtitle */
    margin: 0.5rem 0 0; /* Space between title and subtitle */
    font-weight: 300;
  }

  .center-content .dot {
    margin: 0 0.5rem;
    font-size: 1.5rem; /* Keep the dot the same size as the subtitle */
  }

  /* Footer styling */
  .footer {
    text-align: center;
    padding: 1rem 0;
    background: rgba(0, 0, 0, 0.7); /* Slightly transparent background for readability */
    color: white;
    font-family: 'Poppins', sans-serif;
    font-size: 0.875rem;
  }
</style>



