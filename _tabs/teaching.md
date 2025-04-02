---
layout: page
title: teaching
icon: fas fa-chalkboard-teacher  # optional Font Awesome icon
order: 4           # controls tab order
---

### Teaching Philosophy

Teaching is one of my favorite parts of academic life — I love helping students build intuition around complex Earth systems. My approach to teaching emphasizes curiosity, real-world relevance, and active engagement. I aim to create an inclusive, supportive learning environment where students feel confident asking questions and exploring ideas.

---

### Courses I've been a TA for:

- **CORE 103: Processes of Change in Science** - University of Southern California
  Focus: Social and economic impacts of natural hazards; power and limitations of science to improve our lives through the
worldview of geophysics; interplay of media, government and lobbyists with hazard response.

- **GEOL 240: Earthquakes** – University of Southern California  
  Focus: Causes of earthquakes and nature of large faults; earthquake hazard and risk; world's great earthquakes; understanding the Richter scale.

- **GEOL 160: Introduction to Geosystems** – University of Southern California
  Focus: Survey of natural geological/ environmental processes (systems) and variability active near the earth's surface in the region that houses most life (the biosphere).

- **GEOL 107: Oceanography** – University of Southern California
  Focus: Physical, chemical, and geological character of the oceans andocean basins; ocean processes and agents; economic value of the oceans. 

---

### Student Reviews

<!-- Swiper CSS -->
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"
/>

<style>
  .swiper {
    width: 100%;
    max-width: 600px;
    margin: 2em auto;
    padding: 1em;
  }

  .swiper-slide blockquote {
    font-style: italic;
    margin: 0;
  }

  .swiper-slide footer {
    text-align: right;
    font-size: 0.9em;
    margin-top: 0.5em;
    color: #666;
  }

  .swiper-button-prev,
  .swiper-button-next {
    color: #888;
    width: 30px;
    height: 30px;
    top: 50%;
    transform: translateY(-50%);
  }

  .swiper-button-prev::after,
  .swiper-button-next::after {
    font-size: 20px;
  }

  .swiper-pagination-bullet {
    background: #bbb;
  }

  .swiper-pagination-bullet-active {
    background: #333;
  }
</style>

<div class="swiper mySwiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <blockquote>
        “Brianna explained complex topics so clearly. Her passion for seismology made the class way more engaging!”
        <footer>– GEOL 240 Student, Fall 2024</footer>
      </blockquote>
    </div>
    <div class="swiper-slide">
      <blockquote>
        “Easily one of the most supportive TAs I’ve had — she really cared whether we understood the material.”
        <footer>– Student Evaluation</footer>
      </blockquote>
    </div>
    <div class="swiper-slide">
      <blockquote>
        “Great at answering questions and super approachable. 10/10 would recommend.”
        <footer>– Anonymous Feedback</footer>
      </blockquote>
    </div>
  </div>

  <!-- Pagination (dots) -->
  <div class="swiper-pagination"></div>

  <!-- Navigation (arrows) -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
</div>

<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    new Swiper(".mySwiper", {
      loop: true,
      pagination: {
        el: ".swiper-pagination",
        clickable: true,
      },
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
    });
  });
</script>
