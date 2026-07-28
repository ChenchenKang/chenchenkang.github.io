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
   * Keeps the visible portions of the captions approximately
   * the same height without cutting text automatically.
   */
  .extension-preview {
    min-height: 4.5em;
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
    margin-bottom: 0.4rem;
  }

  .extension-continuation {
    font-size: 0.9rem;
    line-height: 1.5;
  }

  .extension-continuation a {
    display: inline-block;
    margin-top: 0.3rem;
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

    .extension-preview {
      min-height: 0;
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
        Kang participated in the Otis L. Floyd Nursery Research Center Field
        Day, where he presented recent progress and future opportunities for
        robotic spraying in specialty crops and nursery production,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and subsequently hosted a laboratory tour introducing ongoing
          research in agricultural robotics, sensing, precision application,
          and automation for specialty crop production.
          <a href="https://www.facebook.com/share/v/19PRLroSGp/">
            Learn more about NRC Field Day.
          </a>
          
          <a
            href="{{ '/assets/pdf/extension/nrc_field_day.pdf' | relative_url }}"
            target="_blank"
            rel="noopener noreferrer"
          >
            View presentation slides (PDF)
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/home-nursery-visit-2025.jpg' | relative_url }}"
      alt="Kang visiting Home Nursery's Tennessee Farm with Farm Manager Jason Peace"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-10-16">October 16, 2025</time>:
        Kang visited Home Nursery&rsquo;s Tennessee Farm in McMinnville,
        Tennessee, and met with Farm Manager Jason Peace to discuss automation
        technologies for container nursery production,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          including opportunities to reduce labor requirements and improve
          production efficiency. During the visit, Kang examined the farm&rsquo;s
          automated pruning machine and learned how mechanized pruning is
          incorporated into commercial container nursery operations.
          <a href="https://www.homenursery.com/Locations/Tennessee-Farm">
            Learn more about Home Nursery&rsquo;s Tennessee Farm.
          </a>
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
        and labor-saving technologies,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          as well as his decades of practical innovation in production
          systems, irrigation, equipment, and nursery operational efficiency.
          <a href="https://haleandhines.com/terry-hines-featured-in-greenhouse-mgmt/">
            Learn more about Terry Hines.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/blankenship-farms-visit-2025.jpg' | relative_url }}"
      alt="Kang visiting Blankenship Farms and Nursery with grower Jerry Blankenship"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-09-19">September 19, 2025</time>:
        Kang visited Blankenship Farms and Nursery in McMinnville, Tennessee,
        and met with grower Jerry Blankenship to discuss potential robotic
        spraying systems for nursery production,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          including the potential use of drone sprayers to improve application
          efficiency, reduce labor requirements, and address practical spraying
          challenges in commercial nurseries.
          <a href="https://www.blankenshipfarmsandnursery.com/">
            Learn more about Blankenship Farms and Nursery.
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
        precision agriculture technologies,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          along with opportunities for research and extension collaboration
          focused on practical, labor-saving solutions for commercial nursery
          production.
          <a href="https://www.easytreenursery.com/">
            Learn more about Easy Tree Nursery.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/tennessee-small-farm-expo-2025.jpg' | relative_url }}"
      alt="Kang attending the 2025 Tennessee Small Farm Expo"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2025-09-04">September 4, 2025</time>:
        Kang attended the 2025 Tennessee Small Farm Expo at Tennessee State
        University,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          where he connected with farmers, extension professionals, researchers,
          and agricultural organizations. The event provided a valuable
          opportunity to learn more about extension programs, resources, and
          services available to agricultural producers across Tennessee,
          particularly those offered by Tennessee State University and the
          University of Tennessee Institute of Agriculture.
          <a href="https://www.flickr.com/photos/143185401@N03/albums/72177720328849043/">
            Learn more about the Tennessee Small Farm Expo.
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
        Research and Education Center Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          while discussing opportunities to improve spray targeting and canopy
          coverage through robotic control technologies adapted for specialty
          crops.
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
        Center Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and discussed how affordable sensing systems can support
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
        Fruit Research and Extension Center Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          showing how fruit detection and targeted application can improve
          thinning precision while reducing unnecessary chemical use.
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
        Association Summer Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and discussed approaches for adapting robotic spray-control
          technologies to vineyard canopy structures and variable field
          conditions.
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
        production,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          highlighting integrated sensing and imaging approaches for monitoring
          crop growth and improving controlled-environment production
          management.

          <a
            href="{{ '/assets/pdf/extension/mafvc-iot-greenhouse-2025.pdf' | relative_url }}"
            target="_blank"
            rel="noopener noreferrer"
          >
            View presentation slides (PDF)
          </a>
          
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
        disease management at the Mid-Atlantic Fruit and Vegetable Convention,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and explained how localized environmental data can support orchard
          monitoring and more informed disease-management decisions.
          
          <a
            href="{{ '/assets/pdf/extension/mafvc_weather_2025.pdf' | relative_url }}"
            target="_blank"
            rel="noopener noreferrer"
          >
            View presentation slides (PDF)
          </a>
          
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
        Orchard and Lerew Orchards, where participants exchanged ideas about
        pruning, thinning, and pest and disease management,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          as well as labor, equipment, emerging technologies, and other
          challenges faced by apple growers. Kang also gained valuable
          perspectives on how the next generation of growers is adopting new
          technologies and innovative orchard-production practices.
          <a href="https://agsci.psu.edu/research/centers-facilities/extension/frec/yga">
            Learn more about the Young Grower Alliance.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/acn-picking-platform-2024.jpg' | relative_url }}"
      alt="Apple growers attending a harvesting-platform demonstration at an Adams County Nursery orchard"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-08-23">August 23, 2024</time>:
        Kang joined a group of apple growers for a field demonstration of an
        apple-harvesting platform at an Adams County Nursery orchard, where the
        group observed its use during commercial picking operations
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and discussed its effects on harvesting speed, worker organization,
          and orchard workflow. Kang spoke with Adams County Nursery grower
          John Paul Baugher about improvements in picking efficiency and his
          experience managing labor crews with the platform. Kang also exchanged
          perspectives with other growers about the benefits, limitations, and
          practical adoption of harvesting platforms in apple production.
          <a href="https://acnursery.com/">
            Learn more about Adams County Nursery.
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
        State Ag Progress Days,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          illustrating how integrated sensing, imaging, and data technologies
          can improve crop monitoring, production management, and
          sustainability in controlled-environment agriculture.
          <a
            href="{{ '/assets/pdf/extension/agprogress_2024.pdf' | relative_url }}"
            target="_blank"
            rel="noopener noreferrer"
          >
            View presentation slides (PDF)
          </a>
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
        of Maryland Extension Tech Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and discussed the platform&rsquo;s potential applications for
          automated spraying in nursery and specialty crop production.
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/spring-orchard-meeting-2024.jpg' | relative_url }}"
      alt="Kang, Dr. Long He, and Dr. Shanthanu Krishna Kumar attending a drone sprayer demonstration at K. Schlegel Fruit Farm"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-05-08">May 8, 2024</time>:
        Kang attended a Penn State Extension Spring Orchard Meeting at K. Schlegel
        Fruit Farm with Dr. Long He and Dr. Shanthanu Krishna Kumar, where a
        company demonstrated a drone sprayer to growers,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          prompting discussion of the technology&rsquo;s potential benefits,
          practical limitations, and suitability for tree-fruit production.
          The growers&rsquo; strong interest and concerns about spray coverage,
          application volume, effectiveness, maintenance, and cost helped
          motivate subsequent drone-spraying research led by Kumar, with He
          serving as co-principal investigator. Kang also learned more about
          orchard management practices and the production challenges faced by
          commercial fruit growers.
          <a href="https://www.kschlegelfruitfarm.com/">
            Learn more about K. Schlegel Fruit Farm.
          </a>
          <br>
          <a href="https://www.psu.edu/news/research/story/are-drones-future-tree-fruit-production-researchers-investigate">
            Learn more about the drone-spraying research.
          </a>
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
        precision spraying,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          while Erik Quanbeck, High-Value Crops Equipment Sales Manager at
          LandPro Equipment, LLC, demonstrated the Smart Apply precision spray
          system. The group also discussed orchard-management practices and
          production challenges faced by Bobby and Sara.
          <a href="https://www.greensfruitfarm.com/">
            Learn more about Green&rsquo;s Fruit Farm.
          </a>
        </div>
      </details>
    </figcaption>
  </figure>

  <figure class="extension-item">
    <img
      src="{{ '/assets/img/extension/adams-county-nursery-2024.jpg' | relative_url }}"
      alt="Kang and Dr. Long He examining a tree-grading system at Adams County Nursery"
      loading="lazy"
    >
    <figcaption>
      <div class="extension-preview">
        <time class="extension-date" datetime="2024-01-11">January 11, 2024</time>:
        Kang and Dr. Long He visited Adams County Nursery to examine its
        tree-grading system and meet with Adam Baugher, who described the need
        to upgrade the system
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          to reduce manual labor and improve operational efficiency. They
          discussed potential modifications to increase the system&rsquo;s level
          of automation and better support commercial nursery operations.
          <a href="https://acnursery.com/">
            Learn more about Adams County Nursery.
          </a>
          <br>
          <small>Photo credit: Adams County Nursery.</small>
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
        Protection Field Day,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          highlighting the potential of robotic control technologies to improve
          spray targeting and canopy coverage in vineyard production.
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
        Meeting and Trade Show,
      </div>
      <details class="extension-details">
        <summary>Continue reading</summary>
        <div class="extension-continuation">
          and discussed imaging and data-analysis approaches for rapid,
          non-destructive assessment of grapevine nutrient status.
        </div>
      </details>
    </figcaption>
  </figure>

</div>
