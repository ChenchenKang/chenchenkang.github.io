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
      May 7, 2026: Presenting current progress and future opportunities for robotic spraying in specialty crops and nursery production at the 2026 Otis L. Floyd Nursery Research Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/umd_field_day_2025.png' | relative_url }}"
      alt="Field demonstration of a robotic sprayer for improved spray-region control and coverage in raspberries."
      loading="lazy"
    >
    <figcaption>
      July 30, 2025: Demonstrating a robotic sprayer designed to improve control of spray regions and coverage in raspberry production at the 2025 Western Maryland Research and Education Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_field_day_2025.png' | relative_url }}"
      alt="Demonstrating a low-cost orchard sensor station to growers and farmers"
      loading="lazy"
    >
    <figcaption>
      June 25, 2025: Demonstrating a multifunctional, low-cost sensor station for orchard management to growers and farmers at the 2025 Penn State Fruit Research and Extension Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_field_day_spray_2025.png' | relative_url }}"
      alt="Field demonstration of a computer-vision-guided precision sprayer for targeted green fruit chemical thinning."
      loading="lazy"
    >
    <figcaption>
      June 25, 2025: Demonstrating the integration of computer vision and precision sprayers for targeted green fruit chemical thinning to growers and farmers at the 2025 Penn State Fruit Research and Extension Center Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/md_grape.png' | relative_url }}"
      alt="Vineyard field demonstration of a robotic sprayer for improved spray-region control and coverage."
      loading="lazy"
    >
    <figcaption>
      June 21, 2025: Demonstrating a robotic sprayer designed to improve control of spray regions and coverage in vineyards at the 2025 Maryland Grape Growers Association Summer Field Day.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/mafvc_iot_2025.png' | relative_url }}"
      alt="Invited presentation on IoT and computer vision technologies for monitoring soilless greenhouse leafy greens."
      loading="lazy"
    >
    <figcaption>
      January 29, 2025: Invited presentation on IoT and computer vision technologies for monitoring soilless greenhouse leafy greens.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/mafvc_weather_2025.png' | relative_url }}"
      alt="Presentation on a low-cost microclimate monitoring system for orchard disease management."
      loading="lazy"
    >
    <figcaption>
      January 30, 2025: Presenting a low-cost microclimate monitoring system for orchard disease management at the 2025 Mid-Atlantic Fruit and Vegetable Convention.
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/agprogress_2024.png' | relative_url }}"
      alt="Demonstration and presentation of an IoT- and computer-vision-based monitoring system for soilless greenhouse leafy green production."
      loading="lazy"
    >
    <figcaption>
      August 14, 2024: Demonstrating a monitoring system and presenting the use of Internet of Things technologies and computer vision to improve the management and sustainability of soilless greenhouse leafy green production at Penn State’s 2024 Ag Progress Days.
    </figcaption>
  </figure>



</div>
