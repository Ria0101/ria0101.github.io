---
layout: full-width
title: About
---

<style>
  /* Container for the side-by-side layout */
  .profile-container {
    display: flex;
    align-items: center; /* Vertically centers the text with the image */
    gap: 2rem; /* Space between image and text */
    margin-top: 20px;
  }

  /* Image column styling */
  .profile-img {
    flex: 0 0 30%; /* Fixed width of 30% */
    max-width: 300px; /* Prevents image from getting too huge on large screens */
  }

  .profile-img img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1); /* Optional: adds a subtle shadow */
  }

  /* Text column styling */
  .profile-bio {
    flex: 1; /* Takes up remaining space */
    font-size: 1.1rem;
    line-height: 1.6;
  }

  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column; /* Stacks items vertically */
      text-align: center; /* Centers text on mobile */
    }

    .profile-img {
      flex: 0 0 auto;
      width: 60%; /* Make image larger relative to container on mobile */
      margin-bottom: 1.5rem;
    }
  }
</style>

<div class="profile-container">
  <div class="profile-img">
    <img src="/assets/img/bio_photo.jpg" alt="Yuanrui Xu" />
  </div>
  
  <div class="profile-bio">
    <p>
      Yuanrui Xu is a Ph.D. student at Indiana University focusing on postmodern literature, with a special interest in the works of Thomas Pynchon. Her research applies psychoanalytical and schizoanalytical theories to explore ontological questions. 
    </p>
    <p>
      Before joining IU, she earned her BA and MA in English Language and Literature from Peking University, China.
    </p>
    <p>
      In her free time, she’s a music and riddle-solving video games enthusiast, a fan-fiction writer, and an amateur K-pop dancer.
    </p>
  </div>
</div>