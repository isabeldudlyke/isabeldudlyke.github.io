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
    background-image: url("assets/images/tower.jpg"); /* Replace with the path to your profile image */
    flex-shrink: 0;
  }

  /* Contact item wrapper */
  .contact-item {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 1rem;
  }

  /* Contact icons */
  .contact-icon {
    width: 40px;
    height: 40px;
    display: block;
    background-size: cover;
    background-position: center;
    flex-shrink: 0;
  }

  .contact-email {
    background-image: url("assets/icons/email-icon.svg"); /* Replace with your email icon path */
  }

  .contact-linkedin {
    background-image: url("assets/icons/linkedin-icon.svg"); /* Replace with your LinkedIn icon path */
  }

  /* Text next to the icon */
  .contact-details {
    font-size: 1.2rem;
    color: #fff;
    text-align: left;
  }

  .contact-details a {
    color: #0077b5; /* LinkedIn blue for links */
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

    .contact-item {
      gap: 0.5rem;
    }

    .contact-icon {
      width: 30px;
      height: 30px;
    }

    .contact-details {
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
        <div class="contact-details">
          <p>Email:</p>
          <a href="mailto:izzydudlyke@icloud.com">izzydudlyke@icloud.com</a>
        </div>
      </div>

      <!-- LinkedIn Section -->
      <div class="contact-item">
        <div class="contact-icon contact-linkedin"></div>
        <div class="contact-details">
          <p>LinkedIn:</p>
          <a href="https://www.linkedin.com/in/isabel-dudlyke/" target="_blank">LinkedIn Profile</a>
        </div>
      </div>
    </div>
  </div>
</div>

