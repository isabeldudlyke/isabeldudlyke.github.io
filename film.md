---
layout: default
title: "Films"
permalink: /film/
---

<style>
  /* Container that holds all film banners */
  .film-projects-container {
    width: 100%;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }

  /* Each film's banner wrapper */
  .film-banner-wrapper {
    position: relative;
    overflow: hidden;
    cursor: pointer;
    text-decoration: none;
    color: inherit;
  }

  /* Images container: 3 images side by side for large screens */
  .film-images {
    display: flex;
    flex-wrap: nowrap;
    width: 100%;
  }

  .film-images img {
    width: 33.333%;
    height: auto;
    display: block;
    transition: filter 0.3s ease;
  }

  /* Dark overlay on hover */
  .film-banner-wrapper:hover .film-images img {
    filter: brightness(40%);
  }

  /* Centered text container */
  .film-banner-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ffffff; /* White text */
    text-align: center;
    opacity: 0;
    transition: opacity 0.3s ease, transform 0.3s ease;
    font-family: 'Poppins', sans-serif; /* Apply Poppins font */
  }

  /* Text appears on hover */
  .film-banner-wrapper:hover .film-banner-text {
    opacity: 1;
    transform: translate(-50%, -50%) scale(1.05); /* Slight zoom effect */
  }

  /* Style for film title */
  .film-banner-text h2 {
    font-size: 2em; /* Larger font size for title */
    margin: 0;
    font-family: 'Poppins', sans-serif; /* Apply Poppins font */
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7); /* Optional: Adds depth */
  }

  /* Style for film role */
  .film-banner-text p {
    font-size: 1em; /* Smaller font size for role */
    margin: 0;
    font-family: 'Poppins', sans-serif; /* Apply Poppins font */
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7); /* Optional: Adds depth */
  }

  /* Responsive: show only the center image on smaller screens */
  @media (max-width: 768px) {
    .film-images {
      flex-wrap: nowrap;
    }

    .film-images img {
      width: 100%;
      display: none; /* Hide all images by default */
    }

    .film-images img:nth-child(2) {
      display: block; /* Show only the second (center) image */
    }
  }
</style>

<h1>Film Projects</h1>

<div class="film-projects-container">

  <!-- First Project: Tulips -->
  <a href="/tulips.html" class="film-banner-wrapper">
    <div class="film-images">
      <img src="/assets/images/tower.jpg" alt="Tulips banner image 1">
      <img src="/assets/images/tower.jpg" alt="Tulips banner image 2">
      <img src="/assets/images/tower.jpg" alt="Tulips banner image 3">
    </div>
    <div class="film-banner-text">
      <h2>Tulips</h2>
      <p>DP, Director, Editor</p>
    </div>
  </a>

  <!-- Second Project: I am Vertical -->
  <a href="/i-am-vertical.html" class="film-banner-wrapper">
    <div class="film-images">
      <img src="/assets/images/tower.jpg" alt="I am Vertical banner image 1">
      <img src="/assets/images/tower.jpg" alt="I am Vertical banner image 2">
      <img src="/assets/images/tower.jpg" alt="I am Vertical banner image 3">
    </div>
    <div class="film-banner-text">
      <h2>I am Vertical</h2>
      <p>DP, Director, Editor</p>
    </div>
  </a>

</div>
