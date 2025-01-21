---
layout: default
title: "Home"
css_class: Home
---

<div class="center-wrapper">
  <div class="center-box">
    <h1>Isabel Dudlyke</h1>
    <h2>Filmmaker <span class="dot">•</span> Engineer</h2>
  </div>
</div>

<style>
  /* Wrapper ensures footer and header positioning is not disturbed */
  .center-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: calc(100vh - 60px); /* Adjust for header and footer */
    padding-top: 60px; /* Offset for header height */
    padding-bottom: 60px; /* Offset for footer height */
  }

  /* The box that holds the centered text */
  .center-box {
    background-image: url('assets/images/tower.JPG'); /* Path to the background image */
    background-size: cover; /* Ensure the image covers the box */
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Prevent tiling */
    width: 100%; /* Adjust the box width */
    max-width: 1200px; /* Limit maximum width */
    aspect-ratio: 16 / 9; /* Maintain aspect ratio */
    display: flex;
    flex-direction: column; /* Stack name and subtitle vertically */
    justify-content: center;
    align-items: center;
    border-radius: 12px; /* Optional: Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow effect */
    padding: 2rem; /* Add padding inside the box */
  }

  /* Centered content styles */
  .center-box h1 {
    margin: 0;
    color: white;
    font-family: 'Poppins', sans-serif;
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6);
    font-size: 3rem; /* Larger font size for the name */
  }

  .center-box h2 {
    margin: 0.5rem 0 0; /* Space above subtitle */
    color: white;
    font-family: 'Poppins', sans-serif;
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6);
    font-size: 1.5rem; /* Smaller font size for the subtitle */
    font-weight: 300; /* Lighter font for contrast */
  }

  .center-box .dot {
    margin: 0 0.5rem;
    font-size: 1.5rem; /* Match the font size of the subtitle */
  }
</style>




