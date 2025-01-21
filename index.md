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
  /* Wrapper ensures content spans full width and starts below the header */
  .center-wrapper {
    position: absolute;
    top: 60px; /* Height of the header */
    left: 0;
    width: 100%; /* Full width */
    height: calc(100vh - 60px); /* Full viewport height minus header */
    display: flex;
    justify-content: center;
    align-items: center;
  }

  /* Box with the background image */
  .center-box {
    background-image: url('assets/images/tower.JPG'); /* Ensure this path is correct */
    background-size: cover; /* Stretch the image to cover the box */
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Prevent repeating the image */
    width: 100%; /* Full width */
    height: 100%; /* Make the box fill the entire wrapper */
    display: flex;
    flex-direction: column; /* Stack content vertically */
    justify-content: center; /* Center vertically */
    align-items: center; /* Center horizontally */
    text-align: center;
  }

  /* Centered content styling */
  .center-box h1 {
    margin: 0;
    color: white;
    font-family: 'Poppins', sans-serif;
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6); /* Subtle shadow */
    font-size: 4rem; /* Larger font size for the name */
  }

  .center-box h2 {
    margin: 0.5rem 0 0; /* Space above subtitle */
    color: white;
    font-family: 'Poppins', sans-serif;
    text-shadow: 0 4px 6px rgba(0, 0, 0, 0.6); /* Subtle shadow */
    font-size: 1.5rem; /* Smaller font size for the subtitle */
    font-weight: 300; /* Lighter font for contrast */
  }

  .center-box .dot {
    margin: 0 0.5rem;
    font-size: 1.5rem; /* Match the subtitle font size */
  }
</style>




