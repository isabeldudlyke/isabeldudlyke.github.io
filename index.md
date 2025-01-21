---
layout: default
title: "Home"
css_class: Home
---

<div class="center-box">
  <div class="center-content">
    <h1>Isabel Dudlyke</h1>
    <h2>Filmmaker <span class="dot">•</span> Engineer</h2>
  </div>
</div>

<style>
  /* Ensure body background stays clean */
  body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  /* Box setup */
  .center-box {
    background-image: url('tower.jpg'); /* Image for the box */
    background-size: cover; /* Ensure the image covers the entire box */
    background-position: center; /* Center the image in the box */
    background-repeat: no-repeat; /* Prevent the image from repeating */
    width: 100vw; /* Full width of the viewport */
    height: 100vh; /* Full height of the viewport */
    display: flex; /* Flex for centering content inside */
    justify-content: center;
    align-items: center;
  }

  /* Centered content */
  .center-content {
    text-align: center;
    color: white; /* Text color for contrast */
    font-family: 'Poppins', sans-serif; /* Use your chosen font */
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6); /* Add shadow for readability */
  }

  .center-content h1 {
    font-size: 4rem; /* Larger font size for the name */
    margin: 0;
  }

  .center-content h2 {
    font-size: 1.5rem; /* Smaller font size for the subtitle */
    margin: 0.5rem 0 0; /* Add space between name and subtitle */
    font-weight: 300; /* Light font for contrast */
  }

  .center-content .dot {
    margin: 0 0.5rem; /* Space around the dot */
    font-size: 1.5rem;
  }
</style>



