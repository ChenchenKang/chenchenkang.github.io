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
    display: flex;
    flex-direction: column;
    min-width: 0;
    margin: 0;
  }

  .extension-item img {
    display: block;
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 4px;
  }

  .extension-item figcaption {
    margin-top: 0.65rem;
    font-size: 0.95rem;
    line-height: 1.5;
  }

  /*
   * Show exactly three lines when the dropdown is closed.
   * The fixed height keeps cards in the same row aligned.
   */
  .extension-preview {
    display: -webkit-box;
    height: 4.5em;
    overflow: hidden;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 3;
  }

  .extension-date {
    color: var(--global-text-color);
    font-weight: 600;
  }

  .extension-details {
    margin-top: 0.45rem;
  }

  .extension-details summary {
    color: var(--global-theme-color);
    font-size: 0.9rem;
    font-weight: 500;
    cursor: pointer;
  }

  .extension-details summary:hover {
    text-decoration: underline;
  }

  .extension-details summary::marker {
    color: var(--global-theme-color);
  }

  .extension-details[open] summary {
    margin-bottom: 0.45rem;
  }

  .extension-details-content {
    font-size: 0.9rem;
    line-height: 1.5;
  }

  .extension-details-content a {
    display: inline-block;
    margin-top: 0.25rem;
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
      alt="Kang presenting robotic spraying research at the Otis L. Floyd Nursery Research Center Field Day"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2026-05-07">May 7, 2026</time>:
        Kang presented recent progress and future opportunities for robotic
        spraying in specialty crops and nursery production at the Otis L. Floyd
        Nursery Research Center Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          Following the presentation, Kang hosted a laboratory tour and
          introduced ongoing research involving agricultural robotics, sensing,
          precision application, and automation for specialty crop production.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/hale-hines-visit.jpg' | relative_url }}"
      alt="Kang visiting Hale and Hines Nursery with President Terry Hines"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-10-15">October 15, 2025</time>:
        Kang visited Hale &amp; Hines Nursery in McMinnville, Tennessee, where
        President Terry Hines provided a nursery tour and discussed automation
        and labor-saving technologies.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          Hines shared insights from his decades of practical innovation in
          nursery production, including improvements in production systems,
          irrigation, equipment, and operational efficiency.
          <a href="https://haleandhines.com/terry-hines-featured-in-greenhouse-mgmt/">
            Learn more about Terry Hines.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/easy-tree-nursery-visit.jpg' | relative_url }}"
      alt="Kang visiting Easy Tree Nursery with grower James Hines"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-09-15">September 15, 2025</time>:
        Kang visited Easy Tree Nursery in Rock Island, Tennessee, where grower
        James Hines provided a nursery tour and discussed automation and
        precision agriculture technologies.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          As a grower who embraces technology, James shared practical
          perspectives on labor-saving systems and opportunities for research
          and Extension collaboration addressing real nursery production needs.
          <a href="https://www.easytreenursery.com/">
            Learn more about Easy Tree Nursery.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/umd_field_day_2025.png' | relative_url }}"
      alt="Field demonstration of a robotic sprayer for raspberry production"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-07-30">July 30, 2025</time>:
        Kang demonstrated a robotic sprayer designed to improve spray-region
        control and coverage in raspberry production at the Western Maryland
        Research and Education Center Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The demonstration highlighted opportunities to improve spray
          targeting and canopy coverage through robotic control technologies
          adapted for specialty crop production.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_field_day_2025.png' | relative_url }}"
      alt="Kang demonstrating a low-cost orchard sensor station to growers"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-06-25">June 25, 2025</time>:
        Kang demonstrated a multifunctional, low-cost sensor station for
        orchard management at the Penn State Fruit Research and Extension
        Center Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          Kang discussed how affordable sensing systems can support
          microclimate monitoring, disease management, and data-informed
          decision-making in commercial orchards.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_field_day_spray_2025.png' | relative_url }}"
      alt="Demonstration of computer-vision-guided precision spraying for green-fruit thinning"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-06-25">June 25, 2025</time>:
        Kang demonstrated the integration of computer vision and precision
        spraying for targeted green-fruit chemical thinning at the Penn State
        Fruit Research and Extension Center Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The demonstration showed how fruit detection and targeted spraying
          can improve thinning precision while reducing unnecessary chemical
          application.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/md_grape.png' | relative_url }}"
      alt="Vineyard demonstration of a robotic sprayer"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-06-21">June 21, 2025</time>:
        Kang demonstrated a robotic sprayer designed to improve spray-region
        control and coverage in vineyards at the Maryland Grape Growers
        Association Summer Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The demonstration introduced approaches for adapting robotic spray
          control to vineyard canopy structures and variable field conditions.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/mafvc_iot_2025.png' | relative_url }}"
      alt="Invited presentation on IoT and computer vision for greenhouse crop monitoring"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-01-29">January 29, 2025</time>:
        Kang gave an invited presentation on Internet of Things and computer
        vision technologies for monitoring soilless greenhouse leafy green
        production.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The presentation discussed integrated sensing and imaging
          technologies for monitoring crop growth and supporting improved
          management of controlled-environment production systems.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/mafvc_weather_2025.png' | relative_url }}"
      alt="Presentation on a low-cost microclimate monitoring system for orchard disease management"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-01-30">January 30, 2025</time>:
        Kang presented a low-cost microclimate monitoring system for orchard
        disease management at the Mid-Atlantic Fruit and Vegetable Convention.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The presentation introduced an affordable approach to collecting
          localized environmental data that can support orchard monitoring and
          disease-management decisions.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/yga-tour.jpg' | relative_url }}"
      alt="Kang visiting R and L Orchard and Lerew Orchards during the Young Grower Alliance Fall Tour"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-11-19">November 19, 2024</time>:
        Kang attended the Young Grower Alliance Fall Tour and visited R&amp;L
        Orchard and Lerew Orchards to connect with young apple growers.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          Participants exchanged ideas about pruning, crop-load management,
          thinning, pest and disease management, labor, equipment, emerging
          technologies, and other challenges faced by apple growers. The tour
          also provided valuable perspectives on how the next generation of
          growers is adopting new technologies and innovative practices.
          <a href="https://agsci.psu.edu/research/centers-facilities/extension/frec/yga">
            Learn more about the Young Grower Alliance.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/agprogress_2024.png' | relative_url }}"
      alt="Demonstration of an IoT and computer-vision monitoring system at Penn State Ag Progress Days"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-08-14">August 14, 2024</time>:
        Kang demonstrated a monitoring system and presented the use of IoT and
        computer vision for soilless greenhouse leafy green production at Penn
        State Ag Progress Days.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The session showed how integrated sensing, imaging, and data
          technologies can improve crop monitoring, production management, and
          sustainability in controlled-environment agriculture.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/md_nursery_2024.png' | relative_url }}"
      alt="Demonstration of a four-wheel-drive ground robotic sprayer"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-06-20">June 20, 2024</time>:
        Kang demonstrated a four-wheel-drive ground robotic sprayer at the
        Maryland Nursery, Landscape and Greenhouse Association and University
        of Maryland Extension Tech Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The demonstration introduced a mobile robotic platform for
          agricultural spraying and discussed its potential application in
          nursery and specialty crop production.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/greens-fruit-farm-visit-2024.jpg' | relative_url }}"
      alt="Kang and Dr. Long He visiting Green's Fruit Farm"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-03-08">March 8, 2024</time>:
        Kang and Dr. Long He visited Green&rsquo;s Fruit Farm and met with
        growers Bobby and Sara Hricko to discuss orchard production and
        precision spraying.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          Erik Quanbeck, High-Value Crops Equipment Sales Manager at LandPro
          Equipment, LLC, joined the visit and demonstrated the Smart Apply
          precision spray system. The group discussed precision spray
          technologies, orchard management practices, and production
          challenges faced by Bobby and Sara.
          <a href="https://www.greensfruitfarm.com/">
            Learn more about Green&rsquo;s Fruit Farm.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/frec_precision_ag_field_day_2023.png' | relative_url }}"
      alt="Vineyard demonstration of a robotic sprayer at a Penn State Extension field day"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2023-09-15">September 15, 2023</time>:
        Kang demonstrated a robotic sprayer designed to improve spray-region
        control and coverage in vineyards at the Penn State Extension Plant
        Protection Field Day.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The field demonstration introduced robotic spraying technologies
          intended to improve application control and canopy coverage in
          vineyard production.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/wsgs_2022.png' | relative_url }}"
      alt="Presentation on proximal hyperspectral imaging for grapevine nitrogen assessment"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2022-11-17">November 17, 2022</time>:
        Kang presented the use of proximal hyperspectral imaging to assess
        grapevine nitrogen content at the Washington State Grape Society Annual
        Meeting and Trade Show.
      </div>
      <details class="extension-details">
        <summary>More details</summary>
        <div class="extension-details-content">
          The presentation introduced imaging and data-analysis approaches for
          rapid, non-destructive assessment of grapevine nutrient status.
        </div>
      </details>
    </figcaption>
  </figure>

</div>
