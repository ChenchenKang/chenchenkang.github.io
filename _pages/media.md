---
layout: page
title: Media
permalink: /media/
nav: true
nav_order: 4
---

<style>
  /* ==========================================================
     Media page layout
     ========================================================== */

  .media-page {
    margin-top: 1.25rem;
  }

  .media-page .media-section-title {
    margin: 0 0 0.5rem;
    font-size: 1.55rem;
    font-weight: 700;
  }

  .media-page .media-section-title--podcast {
    margin-top: 2.75rem;
  }

  /* Media entry */

  .media-page > .media-entry {
    position: relative;
    box-sizing: border-box;
    align-items: flex-start !important;
    margin-right: 0 !important;
    margin-left: 0 !important;
    padding: 1.4rem 0 !important;
    border: 0 !important;
  }

  /* Clearly visible divider after every entry except the last one */

  .media-page > .media-entry:not(:last-child)::after {
    position: absolute;
    right: 0;
    bottom: 0;
    left: 0;
    display: block;
    height: 1px;
    background-color: rgba(128, 128, 128, 0.55);
    content: "";
  }

  /* Desktop column proportions: 75% text and 25% image */

  @media (min-width: 768px) {
    .media-page .media-entry__content {
      flex: 0 0 75% !important;
      width: 75% !important;
      max-width: 75% !important;
      padding-right: 1.5rem !important;
      padding-left: 0 !important;
    }

    .media-page .media-entry__visual {
      display: flex !important;
      flex: 0 0 25% !important;
      align-items: flex-start !important;
      justify-content: flex-end !important;
      width: 25% !important;
      max-width: 25% !important;
      margin: 0 !important;
      padding: 0 !important;
    }
  }

  /* Title */

  .media-page .media-entry__title {
    margin: 0 0 0.45rem;
    color: var(--global-text-color);
    font-size: 1.15rem;
    font-weight: 650;
    line-height: 1.35;
  }

  /* Publication and date */

  .media-page .media-entry__meta {
    margin: 0 0 0.65rem;
    color: var(--global-text-color-light);
    font-size: 0.92rem;
    line-height: 1.45;
  }

  /* Description */

  .media-page .media-entry__description {
    margin: 0 0 0.7rem;
    font-size: 0.96rem;
    line-height: 1.5;
  }

  .media-page .media-entry__description p {
    margin: 0;
  }

  /* Links */

  .media-page .media-entry__links {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.9rem;
    margin-top: 0.8rem;
  }

  .media-page .media-entry__link {
    display: inline-block;
    margin: 0;
    font-weight: 600;
    text-decoration: none;
  }

  .media-page .media-entry__link:hover {
    text-decoration: underline;
  }

  /* Podcast label */

  .media-page .media-entry__label {
    display: inline-block;
    margin-bottom: 0.45rem;
    padding: 0.15rem 0.5rem;
    color: var(--global-theme-color);
    font-size: 0.75rem;
    font-weight: 650;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    background-color: var(--global-code-bg-color);
    border-radius: 0.25rem;
  }

  /* ==========================================================
     Standardized small images: 220 × 135 px
     ========================================================== */

  .media-page .media-entry__image {
    display: block !important;
    flex: 0 0 220px !important;
    width: 220px !important;
    min-width: 220px !important;
    max-width: 220px !important;
    height: 135px !important;
    overflow: hidden !important;
    border-radius: 0.5rem;
    background-color: var(--global-divider-color);
  }

  .media-page .media-entry__image img {
    display: block !important;
    width: 220px !important;
    min-width: 220px !important;
    max-width: 220px !important;
    height: 135px !important;
    margin: 0 !important;
    padding: 0 !important;
    object-fit: cover !important;
    object-position: center !important;
  }

  /* Reprints */

  .media-page .media-reprints {
    margin-top: 1rem;
    font-size: 0.88rem;
  }

  .media-page .media-reprints__title {
    margin: 0 0 0.4rem;
    color: var(--global-text-color);
    font-size: 0.9rem;
    font-weight: 650;
  }

  .media-page .media-reprints ul {
    margin: 0;
    padding-left: 1.2rem;
  }

  .media-page .media-reprints li {
    margin-bottom: 0.25rem;
    line-height: 1.4;
  }

  .media-page .media-reprints li:last-child {
    margin-bottom: 0;
  }

  .media-page .media-reprints li span {
    color: var(--global-text-color-light);
  }

  /* ==========================================================
     Mobile: text first and small image below
     ========================================================== */

  @media (max-width: 767.98px) {
    .media-page > .media-entry {
      padding: 1.3rem 0 !important;
    }

    .media-page .media-entry__content {
      flex: 0 0 100% !important;
      width: 100% !important;
      max-width: 100% !important;
      padding: 0 !important;
    }

    .media-page .media-entry__visual {
      display: flex !important;
      flex: 0 0 100% !important;
      justify-content: flex-start !important;
      width: 100% !important;
      max-width: 100% !important;
      margin-top: 1rem !important;
      padding: 0 !important;
    }

    .media-page .media-entry__image {
      width: 220px !important;
      min-width: 0 !important;
      max-width: 100% !important;
      height: 135px !important;
    }

    .media-page .media-entry__image img {
      width: 220px !important;
      min-width: 0 !important;
      max-width: 100% !important;
      height: 135px !important;
    }
  }

  @media (max-width: 480px) {
    .media-page .media-entry__title {
      font-size: 1.08rem;
    }

    .media-page .media-entry__links {
      gap: 0.55rem 0.9rem;
    }
  }
</style>



<div class="media-page">
  <h2 class="media-section-title">Articles</h2>

  <!-- =========================================================
       1. Tennessee Greentimes
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Meet Dr. Chenchen Kang
      </h3>

      <p class="media-entry__meta">
        <em>Tennessee Greentimes – Fall 2025</em><br>
        September 15, 2025
      </p>

      <div class="media-entry__description">
        <p>
          A profile of Kang’s background and plans to advance robotics, sensing,
          and AI for nursery production.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://issuu.com/leadingedgepubs/docs/tennessee_greentimes_-_fall_2025/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/tennessee-greentimes-fall-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://issuu.com/leadingedgepubs/docs/tennessee_greentimes_-_fall_2025/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read Meet Dr. Chenchen Kang"
      >
        <img
          src="{{ '/assets/img/media/tennessee-greentimes-2025.jpg' | relative_url }}"
          alt="Meet Dr. Chenchen Kang in Tennessee Greentimes"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       2. Lancaster Farming
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Variable-rate spraying shows promise in orchards
      </h3>

      <p class="media-entry__meta">
        Philip Gruber, <em>Lancaster Farming</em><br>
        June 26, 2025
      </p>

      <div class="media-entry__description">
        <p>
          This article highlights variable-rate spraying as a way to reduce
          chemical use in orchards.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://www.lancasterfarming.com/farming-news/produce/variable-rate-spraying-shows-promise-in-orchards/article_d4fac63d-cd6c-4e1e-b348-0fc8dcd5ee87.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/lancaster-farming-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://www.lancasterfarming.com/farming-news/produce/variable-rate-spraying-shows-promise-in-orchards/article_d4fac63d-cd6c-4e1e-b348-0fc8dcd5ee87.html"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read Variable-rate spraying shows promise in orchards"
      >
        <img
          src="{{ '/assets/img/media/variable-rate-spraying-orchards-2025.jpg' | relative_url }}"
          alt="Variable-rate spraying research in an orchard"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       3. Vision Systems Design
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Machine vision system monitors greenhouse-grown specialty crop
      </h3>

      <p class="media-entry__meta">
        Linda Wilson, <em>Vision Systems Design Magazine</em><br>
        March 21, 2025
      </p>

      <div class="media-entry__description">
        <p>
          A technical overview of an AI- and IoT-based computer-vision system
          for greenhouse crop monitoring.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://www.vision-systems.com/boards-software/article/55276457/machine-vision-system-monitors-greenhouse-grown-specialty-crop"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/vision-systems-design-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://www.vision-systems.com/boards-software/article/55276457/machine-vision-system-monitors-greenhouse-grown-specialty-crop"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read the Vision Systems Design article"
      >
        <img
          src="{{ '/assets/img/media/machiane-vision-greenhouse-crop-2025.jpg' | relative_url }}"
          alt="Computer vision system monitoring greenhouse-grown crops"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       4. Quantum Zeitgeist
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        New computer vision system with IoT and AI enhances specialty crops monitoring in greenhouses
      </h3>

      <p class="media-entry__meta">
        <em>Quantum Zeitgeist</em><br>
        March 5, 2025
      </p>

      <div class="media-entry__description">
        <p>
          This article features an AI- and IoT-enabled system for automated
          greenhouse crop monitoring.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://quantumzeitgeist.com/new-computer-vision-system-with-iot-and-ai-enhances-specialty-crops-monitoring-in-greenhouses/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/quantum-zeitgeist-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://quantumzeitgeist.com/new-computer-vision-system-with-iot-and-ai-enhances-specialty-crops-monitoring-in-greenhouses/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read the Quantum Zeitgeist article"
      >
        <img
          src="{{ '/assets/img/media/machiane-vision-greenhouse-crop-2025.jpg' | relative_url }}"
          alt="Greenhouse computer vision, IoT, and AI monitoring system"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       5. Bioengineer.org
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Innovative computer vision system enhances monitoring of specialty crops
      </h3>

      <p class="media-entry__meta">
        <em>Bioengineer.org</em><br>
        March 4, 2025
      </p>

      <div class="media-entry__description">
        <p>
          This article presents a computer-vision platform for monitoring crop
          growth and greenhouse conditions.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://bioengineer.org/innovative-computer-vision-system-enhances-monitoring-of-specialty-crops/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/bioengineer-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://bioengineer.org/innovative-computer-vision-system-enhances-monitoring-of-specialty-crops/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read the Bioengineer.org article"
      >
        <img
          src="{{ '/assets/img/media/machiane-vision-greenhouse-crop-2025.jpg' | relative_url }}"
          alt="Computer vision monitoring of greenhouse specialty crops"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       6. Fertilizer Daily
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Penn State researchers programmed AI models and trained computer vision system to track plant growth
      </h3>

      <p class="media-entry__meta">
        Timothy Bueno, <em>Fertilizer Daily</em><br>
        March 3, 2025
      </p>

      <div class="media-entry__description">
        <p>
          This article describes the use of AI and computer vision to automate
          plant-growth tracking.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://www.fertilizerdaily.com/20250303-penn-state-researchers-programmed-ai-models-and-trained-computer-vision-system-to-track-plant-growth/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/fertilizer-daily-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://www.fertilizerdaily.com/20250303-penn-state-researchers-programmed-ai-models-and-trained-computer-vision-system-to-track-plant-growth/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read the Fertilizer Daily article"
      >
        <img
          src="{{ '/assets/img/media/machiane-vision-greenhouse-crop-2025.jpg' | relative_url }}"
          alt="AI-based computer vision system tracking plant growth"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       7. Penn State News
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        New computer vision system can guide specialty crops monitoring
      </h3>

      <p class="media-entry__meta">
        Jeff Mulhollem, <em>The Pennsylvania State University</em><br>
        February 27, 2025
      </p>

      <div class="media-entry__description">
        <p>
          This release introduces a computer-vision and IoT system for
          continuous greenhouse crop monitoring.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://www.psu.edu/news/research/story/new-computer-vision-system-can-guide-specialty-crops-monitoring"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/penn-state-news-2025.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>

      <div class="media-reprints">
        <p class="media-reprints__title">
          Reprints and syndication
        </p>

        <ul>
          <li>
            <a
              href="https://phys.org/news/2025-02-vision-tracks-growth-specialty-crop.html"
              target="_blank"
              rel="noopener noreferrer"
            >
              Phys.org
            </a>
            <span>— February 27, 2025</span>
          </li>

          <li>
            <a
              href="https://www.eurekalert.org/multimedia/1063074"
              target="_blank"
              rel="noopener noreferrer"
            >
              EurekAlert!
            </a>
            <span>— February 27, 2025</span>
          </li>

          <li>
            <a
              href="https://www.hortidaily.com/article/9709666/new-computer-vision-system-guiding-crop-monitoring/"
              target="_blank"
              rel="noopener noreferrer"
            >
              HortiDaily
            </a>
            <span>— February 28, 2025</span>
          </li>

          <li>
            <a
              href="https://tiisys.com/blog/2025/02/28/post-161981/"
              target="_blank"
              rel="noopener noreferrer"
            >
              Tech-I Technology Information Research Institute
            </a>
            <span>— February 28, 2025</span>
          </li>

          <li>
            <a
              href="https://www.sciencedaily.com/releases/2025/03/250304164416.htm"
              target="_blank"
              rel="noopener noreferrer"
            >
              ScienceDaily
            </a>
            <span>— March 4, 2025</span>
          </li>

          <li>
            <a
              href="https://www.enn.com/articles/76114-new-computer-vision-system-can-guide-specialty-crops-monitoring"
              target="_blank"
              rel="noopener noreferrer"
            >
              Environment News Network
            </a>
            <span>— March 5, 2025</span>
          </li>
        </ul>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://www.psu.edu/news/research/story/new-computer-vision-system-can-guide-specialty-crops-monitoring"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read the Penn State research release"
      >
        <img
          src="{{ '/assets/img/media/machiane-vision-greenhouse-crop-2025.jpg' | relative_url }}"
          alt="Penn State greenhouse specialty-crop monitoring system"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       8. Good Fruit Grower
       ========================================================= -->

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <h3 class="media-entry__title">
        Spectrum smart vineyard irrigation
      </h3>

      <p class="media-entry__meta">
        Kate Prengaman, <em>Good Fruit Grower Magazine</em><br>
        August 19, 2021
      </p>

      <div class="media-entry__description">
        <p>
          This article explores sensing technologies for assessing grapevine
          water status and improving irrigation.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://www.goodfruit.com/spectrum-smart-vineyard-irrigation/"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read full article →
        </a>

        <a
          class="media-entry__link"
          href="{{ '/assets/pdf/media/good-fruit-grower-2021.pdf' | relative_url }}"
          target="_blank"
          rel="noopener noreferrer"
        >
          View PDF →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://www.goodfruit.com/spectrum-smart-vineyard-irrigation/"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Read Spectrum smart vineyard irrigation"
      >
        <img
          src="{{ '/assets/img/media/good-fruit-grower-2021.jpg' | relative_url }}"
          alt="Smart sensing and irrigation research in a vineyard"
          loading="lazy"
        >
      </a>
    </div>
  </div>


  <!-- =========================================================
       Podcast
       ========================================================= -->

  <h2 class="media-section-title media-section-title--podcast">
    Podcast
  </h2>

  <div class="media-entry row align-items-start">
    <div class="media-entry__content col-md-8">
      <span class="media-entry__label">
        Podcast episode
      </span>

      <h3 class="media-entry__title">
        Challenges of developing field sensors
      </h3>

      <p class="media-entry__meta">
        Patricia A. Skinkis,
        <em>HiRes Vineyard Nutrition Podcast</em><br>
        November 2023
      </p>

      <div class="media-entry__description">
        <p>
          This episode discusses the challenges of developing and deploying
          vineyard sensing technologies.
        </p>
      </div>

      <div class="media-entry__links">
        <a
          class="media-entry__link"
          href="https://extension.oregonstate.edu/podcast/hires-vineyard-nutrition-podcast/season-2-episode-4-challenges-developing-field-sensors"
          target="_blank"
          rel="noopener noreferrer"
        >
          Listen to episode →
        </a>
      </div>
    </div>

    <div class="media-entry__visual col-md-4">
      <a
        class="media-entry__image"
        href="https://extension.oregonstate.edu/podcast/hires-vineyard-nutrition-podcast/season-2-episode-4-challenges-developing-field-sensors"
        target="_blank"
        rel="noopener noreferrer"
        aria-label="Listen to Challenges of developing field sensors"
      >
        <img
          src="{{ '/assets/img/media/hires-vineyard-podcast-2023.jpg' | relative_url }}"
          alt="HiRes Vineyard Nutrition Podcast"
          loading="lazy"
        >
      </a>
    </div>
  </div>
</div>
