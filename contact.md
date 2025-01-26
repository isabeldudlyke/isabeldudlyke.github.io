---
layout: default
title: "Contact"
permalink: /contact/
css_class: "contact-page"
---

<style>
  /* Container for contact information */
  .contact-page-container {
    width: 100%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 3rem 1rem;
    text-align: center;
  }

  /* Profile and contact details layout */
  .contact-section {
    display: flex;
    align-items: flex-start; /* Align text to top of the photo */
    justify-content: center;
    gap: 2rem;
  }

  /* Circular profile image */
  .profile-image {
    width: 300px; /* Larger image */
    height: 300px;
    border-radius: 50%;
    background-size: cover;
    background-position: left center; /* Adjust to show the leftmost part of the image */
    background-image: url("/assets/images/IMG_5332.jpeg"); /* Ensure correct file path */
    flex-shrink: 0;
  }

  /* Contact details container */
  .contact-details-container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start; /* Align title with top of the image */
    text-align: left;
  }

  /* Title styling */
  .contact-details-container h1 {
    font-size: 3rem; /* Larger title */
    color: #ddd; /* Lighter color for the title */
    margin-bottom: 1.5rem;
  }

  /* Contact item wrapper */
  .contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 1.5rem;
  }

  /* Contact icons */
  .contact-icon {
    width: 40px; /* Larger icons */
    height: 40px;
    display: block;
    background-size: cover;
    background-position: center;
  }

  .contact-email {
    background-image: url("/assets/icons/github.svg"); /* Correct path */
  }

  .contact-linkedin {
    background-image: url("/assets/icons/linkedin.svg"); /* Correct path */
  }

  /* Contact text */
  .contact-details-container a {
    font-size: 1.5rem; /* Bigger text */
    color: #0077b5; /* Link color */
    text-decoration: none;
    font-weight: bold;
  }

  .contact-details-container a:hover {
    text-decoration: underline;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .contact-section {
      flex-direction: column;
      align-items: center;
    }

    .profile-image {
      width: 150px;
      height: 150px;
    }

    .contact-details-container {
      text-align: center;
    }

    .contact-icon {
      width: 30px;
      height: 30px;
    }

    .contact-details-container a {
      font-size: 1.2rem;
    }
  }
</style>

<div class="contact-page-container">
  <div class="contact-section">
    <!-- Profile Image -->
    <div class="profile-image"></div>

    <!-- Contact Details -->
    <div class="contact-details-container">
      <h1>Get in Touch</h1>
      <!-- Email Section -->
      <div class="contact-item">
        <div class="contact-icon contact-email"></div>
        <a href="mailto:izzydudlyke@icloud.com">izzydudlyke@icloud.com</a>
      </div>
      <!-- LinkedIn Section -->
      <div class="contact-item">
        <div class="contact-icon contact-linkedin"></div>
        <a href="https://www.linkedin.com/in/isabel-dudlyke/" target="_blank">LinkedIn Profile</a>
      </div>
    </div>
  </div>
</div>
