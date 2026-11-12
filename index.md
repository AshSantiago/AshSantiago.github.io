---
layout: splash
title: "Ashley Santiago"
permalink: /
header:
  overlay_image: /assets/landscape.jpg
  overlay_filter: 0.45
  actions:
    - label: "Explore my research"
      url: "/research"
excerpt: "Ph.D. student in Ecology, Evolution, and Behavior at Boise State University studying Golden Eagle population dynamics."

bio_row:
  - image_path: /assets/profile.jpg
    alt: "Ashley Santiago in the field"
    excerpt: "I am currently a researcher in the <a href="https://www.boisestate.edu/biology-gcebirds/" target="_blank">Heath Lab</a> at Boise State University, where I study Golden Eagle ecology and population dynamics. My work integrates field ecology, statistical modeling, and genomic approaches to uncover the drivers of population decline and guide conservation efforts."
    url: "/about"
    btn_label: "More about me"
    btn_class: "btn--primary"

research_intro:
  - excerpt: "## Research\n\nMy current work focuses on territory occupancy, juvenile survival, and adult turnover of the Golden Eagle population in southwestern Idaho."

feature_row:
  - image_path: /assets/occupancy.png
    alt: "Territory occupancy"
    title: "Territory Occupancy"
    excerpt: "**Territory Ecology.** How landscape attributes shape breeding territory occupancy."
    url: "/research-occupancy"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/nestling.png
    alt: "Golden Eagle nestling"
    title: "First-year Survival"
    excerpt: "**Survival Analysis.** How nest parasites and disease affect juvenile survival."
    url: "/research-survival"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/adult_DNA.png
    alt: "Adult Golden Eagle and DNA"
    title: "Adult Turnover"
    excerpt: "**Population Genomics.** Using genetic mark-recapture to estimate breeding adult survival and turnover."
    url: "/research-turnover"
    btn_label: "Read more"
    btn_class: "btn--primary"
---

{% include feature_row id="bio_row" type="left" %}

{% include feature_row id="research_intro" type="center" %}

{% include feature_row %}

<!-- Interactive field-site map (your custom piece; kept as HTML) -->
<style>
  .field-site { position: relative; max-width: 1100px; margin: 0 auto 3rem; user-select: none; }
  .field-site > img { width: 100%; display: block; border-radius: 12px; }
  .nav-icon {
    position: absolute; display: flex; flex-direction: column; align-items: center;
    text-decoration: none; transition: transform 0.25s ease; z-index: 2;
  }
  .nav-icon:hover { transform: translateY(-14px); z-index: 10; }
  .nav-icon img { display: block; width: 100%; filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3)); transition: filter 0.25s ease; }
  .nav-icon:hover img { filter: drop-shadow(0 10px 20px rgba(0,0,0,0.5)) brightness(1.08); }
  .nav-bubble {
    position: absolute; bottom: calc(100% + 10px); left: 50%;
    transform: translateX(-50%) translateY(4px);
    background: #fff; color: #2c3828; font-size: 0.85rem; font-weight: 700;
    padding: 0.45rem 1.1rem; border-radius: 20px; white-space: nowrap;
    opacity: 0; pointer-events: none; transition: opacity 0.2s ease, transform 0.2s ease;
    box-shadow: 0 3px 14px rgba(0,0,0,0.25); z-index: 20;
  }
  .nav-bubble::after {
    content: ''; position: absolute; top: 100%; left: 50%; transform: translateX(-50%);
    border: 7px solid transparent; border-top-color: #fff;
  }
  .nav-icon:hover .nav-bubble { opacity: 1; transform: translateX(-50%) translateY(0); }

  /* Phones and tablets can't hover, so show the labels all the time */
  @media (hover: none) {
    .nav-bubble { opacity: 1; transform: translateX(-50%); font-size: 0.65rem; padding: 0.25rem 0.6rem; }
  }
</style>

<div style="text-align: center; margin: 3rem 0 1.5rem;">
  <p style="font-size: 0.8rem; letter-spacing: 0.2em; text-transform: uppercase; margin-bottom: 0.3rem;">Explore</p>
  <h2 style="margin: 0;">Click around the field site</h2>
</div>

<div class="field-site">
  <img src="/assets/Nav_map_blank.png" alt="Field site navigation scene">

  <a class="nav-icon" href="/research" style="top: 23.5%; left: 24%; width: 24.5%;">
    <div class="nav-bubble">Research</div>
    <img src="/assets/eagle_soar.png" alt="Eagle">
  </a>

  <a class="nav-icon" href="/publications" style="top: 37.5%; left: 46.5%; width: 28%;">
    <div class="nav-bubble">Publications</div>
    <img src="/assets/truck.png" alt="Truck">
  </a>

  <a class="nav-icon" href="/about" style="top: 28%; left: 65%; width: 14%;">
    <div class="nav-bubble">About</div>
    <img src="/assets/person.png" alt="Person with binoculars">
  </a>

  <a class="nav-icon" href="/contact" style="top: 23.5%; left: 59%; width: 12%;">
    <div class="nav-bubble">Contact</div>
    <img src="/assets/scope.png" alt="Spotting scope">
  </a>

  <a class="nav-icon" href="/cv" style="top: 34%; left: 74%; width: 9%;">
    <div class="nav-bubble">CV</div>
    <img src="/assets/backpack.png" alt="Backpack">
  </a>
</div>
