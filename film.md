---
layout: default
title: "Contact"
permalink: /contact/
css_class: "contact-page"
---

<style>
  /* Container for contact information */
  .contact-page-container {
    display: flex;
    align-items: center; /* Align items vertically */
    justify-content: space-between; /* Spread content */
    width: 80%;
    margin: 0 auto;
    padding: 2rem 0;
  }

  /* Profile image styling */
  .profile-image {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background-size: cover;
    background-position: center;
    background-image: url("/assets/images/IMG_5332.jpeg"); /* Ensure the file path is correct */
    flex-shrink: 0;
  }

  /* Contact information container */
  .contact-info {
    text-align: right;
    flex-grow: 1;
    margin-left: 2rem;
  }

  /* Title styling */
  .contact-info h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #333;
  }

  /* Contact item wrapper */
  .contact-item {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    gap: 1rem;
    margin-bottom: 1rem;
  }

  /* Contact icon */
  .contact-icon {
    width: 24px;
    height: 24px;
    background-size: cover;
    background-position: center;
    flex-shrink: 0;
  }

  .contact-email {
    background-image: url("/assets/icons/github.svg");
  }

  .contact-linkedin {
    background-image: url("/assets/icons/linkedin.svg");
  }

  /* Contact details text */
  .contact-details a {
    font-size: 1.2rem;
    color: #0077b5;
    text-decoration: none;
    font-weight: bold;
  }

  .contact-details a:hover {
    text-decoration: underline;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .contact-page-container {
      flex-direction: column;
      align-items: center;
    }

    .contact-info {
      text-align: center;
      margin-left: 0;
    }

    .contact-item {
      justify-content: center;
    }
  }
</style>

<div class="contact-page-container">
  <!-- Profile Image -->
  <div class="profile-image"></div>

  <!-- Contact Info -->
  <div class="contact-info">
    <h1>Get in Touch</h1>
    <div class="contact-item">
      <div class="contact-icon contact-email"></div>
      <a href="mailto:izzydudlyke@icloud.com">izzydudlyke@icloud.com</a>
    </div>
    <div class="contact-item">
      <div class="contact-icon contact-linkedin"></div>
      <a href="https://www.linkedin.com/in/isabel-dudlyke/" target="_blank">LinkedIn Profile</a>
    </div>
  </div>
</div>
