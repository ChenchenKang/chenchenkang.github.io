---
layout: page
title: Extension
permalink: /extension/
description: Extension activities and community engagement.
nav: true
nav_order: 5
---

<style>
  .extension-gallery {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 2rem 1.5rem;
    margin-top: 1.5rem;
  }

  .extension-item {
    margin: 0;
  }

  .extension-item img {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    display: block;
    border-radius: 4px;
  }

  .extension-item figcaption {
    margin-top: 0.65rem;
    font-size: 0.95rem;
    line-height: 1.5;
  }

  @media (max-width: 768px) {
    .extension-gallery {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 576px) {
    .extension-gallery {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="extension-gallery">

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/nrc_field_day.png' | relative_url }}"
      alt="Extension activity at the Nursery Research Center"
      loading="lazy"
    >
    <figcaption>
      Presenting current progress and future opportunities for robotic spraying in specialty crops and nursery production at the 2026 Otis L. Floyd Nursery Research Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_field_day_2025.png' | relative_url }}"
      alt="Drone demonstration for agricultural applications"
      loading="lazy"
    >
    <figcaption>
      Demonstrating a multifunctional, low-cost sensor station for orchard management to growers and farmers at the 2025 Penn State Fruit Research and Extension Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/extension-03.jpg' | relative_url }}"
      alt="Agricultural robotics demonstration"
      loading="lazy"
    >
    <figcaption>
      Demonstrating agricultural robotics and automation technologies for specialty crop production.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/extension-04.jpg' | relative_url }}"
      alt="Field demonstration with growers"
      loading="lazy"
    >
    <figcaption>
      Engaging with growers through field demonstrations of sensing and precision management technologies.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/extension-05.jpg' | relative_url }}"
      alt="Student and community outreach activity"
      loading="lazy"
    >
    <figcaption>
      Supporting agricultural education through hands-on activities for students and community participants.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/extension-06.jpg' | relative_url }}"
      alt="Precision agriculture equipment presentation"
      loading="lazy"
    >
    <figcaption>
      Presenting precision agriculture equipment and research projects to visitors and industry stakeholders.
    </figcaption>
  </figure>

</div>
