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
    flex-direction: column;
    gap: 2rem;
    text-align: center;
  }

  /* Profile and contact details layout */
  .contact-section {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2rem;
    padding: 2rem 0;
  }

  /* Circular profile image */
  .profile-image {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background-size: cover;
    background-position: center;
    background-image: url("/assets/images/tower.jpg"); /* Ensure correct file path */
    flex-shrink: 0;
  }

  /* Contact item wrapper */
  .contact-item {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    margin-bottom: 1rem;
  }

  /* Contact icons */
  .contact-icon {
    width: 24px;
    height: 24px;
    display: block;
    background-size: cover;
    background-position: center;
    flex-shrink: 0;
  }

  .contact-email {
    background-image: url("/assets/icons/github.svg"); /* Correct icon path */
  }

  .contact-linkedin {
    background-image: url("/assets/icons/linkedin.svg"); /* Correct icon path */
  }

  /* Contact text */
  .contact-details a {
    font-size: 1.2rem;
    color: #0077b5; /* Link color */
    text-decoration: none;
    font-weight: bold;
  }

  .contact-details a:hover {
    text-decoration: underline;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .contact-section {
      flex-direction: column;
    }

    .profile-image {
      width: 100px;
      height: 100px;
    }

    .contact-icon {
      width: 20px;
      height: 20px;
    }

    .contact-details a {
      font-size: 1rem;
    }
  }
</style>

# Get in Touch

<div class="contact-page-container">
  <div class="contact-section">
    <!-- Profile Image -->
    <div class="profile-image"></div>

    <!-- Contact Details -->
    <div>
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

