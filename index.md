---
layout: default
title: The Best Private Soccer Training in Charlotte | Queen City Standouts
description: Elite private soccer training in Charlotte, NC. 1-on-1 and small group sessions designed to help serious players stand out.
permalink: /
---

<!-- ========================= -->
<!-- HERO SECTION -->
<!-- ========================= -->
<section class="hero">
  <div
    class="hero-image"
    style="background-image: url('{{ "/assets/img/hero-soccer.jpg" | relative_url }}');"
  ></div>

  <div class="hero-text">
    <h1>The Best Private Soccer Training in Charlotte</h1>
    <p>Elite 1-on-1 & small group soccer training for serious players</p>
    <a href="#contact" class="btn btn-primary btn-hero">
      Book Your First Session
    </a>
  </div>
</section>

<!-- ========================= -->
<!-- SERVICES SECTION -->
<!-- ========================= -->
<section id="services" class="page-section">
  <div class="container">
    <div class="text-center">
      <h2 class="section-heading text-uppercase">Training Services</h2>
      <p class="section-subheading text-muted">
        Personalized soccer training built to help players excel.
      </p>
    </div>

    <div class="row text-center">
      <div class="col-md-4">
        <h4 class="my-3">Private 1-on-1 Training</h4>
        <p class="text-muted">
          Individualized sessions focused on technical mastery, speed,
          confidence, and game intelligence.
        </p>
      </div>

      <div class="col-md-4">
        <h4 class="my-3">Small Group Training</h4>
        <p class="text-muted">
          High-intensity group sessions designed to simulate real-game pressure
          while maintaining personal attention.
        </p>
      </div>

      <div class="col-md-4">
        <h4 class="my-3">Player Development Plans</h4>
        <p class="text-muted">
          Long-term development strategies tailored to each athlete’s goals,
          position, and level.
        </p>
      </div>
    </div>
  </div>
</section>

<!-- ========================= -->
<!-- PORTFOLIO / RESULTS -->
<!-- ========================= -->
<section id="portfolio" class="page-section bg-light">
  <div class="container">
    <div class="text-center">
      <h2 class="section-heading text-uppercase">Player Results</h2>
      <p class="section-subheading text-muted">
        Real players. Real improvement.
      </p>
    </div>

    {% include portfolio-grid.html %}
  </div>
</section>

<!-- ========================= -->
<!-- ABOUT -->
<!-- ========================= -->
<section id="about" class="page-section">
  <div class="container">
    <div class="text-center">
      <h2 class="section-heading text-uppercase">About Queen City Standouts</h2>
      <p class="section-subheading text-muted">
        Building confident, disciplined, and elite soccer players.
      </p>
    </div>

    <p class="text-center">
      Queen City Standouts is dedicated to developing high-level soccer players
      through focused training, mentorship, and accountability. Our mission is
      to help athletes stand out on and off the field.
    </p>
  </div>
</section>

<!-- ========================= -->
<!-- CONTACT -->
<!-- ========================= -->
<section id="contact" class="page-section">
  <div class="container">
    <div class="text-center">
      <h2 class="section-heading text-uppercase">Contact Us</h2>
      <p class="section-subheading text-muted">
        Book your first session today.
      </p>
    </div>

    {% include contact.html %}
  </div>
</section>
