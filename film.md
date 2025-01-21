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
  .film-banner-wrapper:hover img {
    filter: brightness(40%);
  }

  /* Centered text */
  .film-banner-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #ffffff;
    text-align: center;
    opacity: 0;
    transition: opacity 0.3s ease;
  }

  .film-banner-wrapper:hover .film-banner-text {
    opacity: 1;
  }

  /* Responsive: collapse images into one column on smaller screens */
  @media (max-width: 768px) {
    .film-images {
      flex-wrap: wrap;
    }
    .film-images img {
      width: 100%;
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
