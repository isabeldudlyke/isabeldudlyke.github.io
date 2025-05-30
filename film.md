---
layout: default
title: "Film"
permalink: /film/
css_class: "film-page"
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
    height: 250px; /* Set a consistent banner height */

  }

  .film-images img {
    width: 33.333%;
    height: 100%; /* Force uniform height */
    object-fit: cover; /* Ensures image fills area without distortion */
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
    color: #ffffff !important; /* White text */
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
    color: #ffffff !important; /* Ensure white text */
    font-family: 'Poppins', sans-serif; /* Apply Poppins font */
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7); /* Optional: Adds depth */
    letter-spacing: 0.05em; /* Add letter spacing */
    word-spacing: 0.1em; /* Add word spacing */
    font-weight: 700; /* Bold font for title */
    white-space: normal; /* Ensure normal spacing */
  }

  /* Style for film role */
  .film-banner-text p {
    font-size: 1em; /* Smaller font size for role */
    margin: 0;
    color: #ffffff !important; /* Ensure white text */
    font-family: 'Poppins', sans-serif; /* Apply Poppins font */
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7); /* Optional: Adds depth */
    letter-spacing: 0.02em; /* Add slight letter spacing */
    word-spacing: 0.05em; /* Add slight word spacing */
    font-weight: 400; /* Normal font weight for role */
  }

  /* Responsive: show only the center image on smaller screens */
  @media (max-width: 768px) {
    .film-images {
      flex-wrap: nowrap;
      height: 250px; /* Keep the same fixed height on mobile */
    }

  .film-images img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: none;
  }

  .film-images img:nth-child(2) {
    display: block;
  }
}
    /* Smaller Title for Film Projects */
  .film-page h1 {
    font-size: 2rem; /* Adjust this value for the desired size */
    margin-bottom: 1rem; /* Optional: Adjust spacing below the title */
  }
</style>

# Film Portfolio

---
<div class="film-projects-container">
  {% assign sorted_films = site.film | sort: "priority" %}
  {% for fi in sorted_films %}
    <a href="{{ fi.url }}" class="film-banner-wrapper" aria-label="View details for {{ fi.title }}">
      <div class="film-images">
        {% for image in fi.images %}
          <img src="{{ image | relative_url }}" alt="{{ fi.title }} banner image {{ forloop.index }}" loading="lazy">
        {% endfor %}
      </div>
      <div class="film-banner-text">
        <h2>{{ fi.title }}</h2>
        <p>{{ fi.roles }}</p>
      </div>
    </a>
  {% endfor %}
</div>
