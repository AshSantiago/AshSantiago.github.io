---
layout: default
title: Home
---

<!-- Full-bleed landscape banner -->
<div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; height: 460px; overflow: hidden; margin-bottom: 0;">
  <img src="assets/landscape.jpg" alt="Sagebrush steppe landscape"
       style="width: 100%; height: 100%; object-fit: cover; object-position: center 40%;"
       onerror="this.parentElement.style.background='#5a7a4a'; this.style.display='none';">
  <div style="position: absolute; inset: 0; background: linear-gradient(to bottom, transparent 50%, rgba(247,243,238,0.15) 100%);"></div>
</div>

<!-- Profile photo + Bio — centered card lifted over banner -->
<div style="max-width: 860px; margin: -80px auto 0; padding: 0 2rem; position: relative; z-index: 2;">
  <div style="background: #f7f3ee; border-radius: 12px; box-shadow: 0 8px 40px rgba(44,40,32,0.13); padding: 2.5rem 3rem; display: flex; align-items: center; gap: 2.5rem;">
    <img src="assets/profile.jpg" alt="Ashley Santiago"
         style="width: 200px; height: 200px; object-fit: cover; object-position: center top; border-radius: 50%; flex-shrink: 0; box-shadow: 0 4px 18px rgba(74,63,53,0.18); border: 4px solid #dde6d5;">
    <div>
      <h1 style="margin: 0 0 0.3rem; font-size: 2.2rem;">Ashley Santiago</h1>
      <p style="margin: 0 0 1rem; color: #5a7a4a; font-style: italic; font-size: 1rem;">Ph.D. Student · Ecology, Evolution, and Behavior · Boise State University · Raptor Research Center</p>
      <p style="font-size: 1.05rem; line-height: 1.85; margin: 0; color: #2c2820;">
      I am currently studying Golden Eagle ecology, survival, and population dynamics, combining field ecology with 
      statistical modeling and novel genomic approaches to understand the potential drivers of population decline and inform 
      conservation strategies. I work in the <a href="https://www.heathlab.com" target="_blank">Heath Lab</a> at Boise State University.
      </p>
    </div>
  </div>
</div>

<!-- Research section -->
<div style="max-width: 860px; margin: 4rem auto 3rem; padding: 0 2rem;">

  <div style="text-align: center; margin-bottom: 2.5rem;">
    <h2 style="font-size: 1.6rem; margin-bottom: 0.6rem;">Research</h2>
    <p style="font-size: 1.05rem; line-height: 1.75; color: #6b6259; max-width: 600px; margin: 0 auto;">
      My work integrates long-term field data, statistical modeling, and genomics to understand raptor population dynamics and inform conservation management.
    </p>
  </div>

  <div style="display: flex; justify-content: center; gap: 3rem; flex-wrap: wrap; margin-bottom: 2rem;">

    <!-- Territory Occupancy -->
    <a href="research-occupancy" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1rem; width: 280px;">
      <div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 16px rgba(90,122,74,0.45))'; this.style.transform='translateY(-5px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/occupancy.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
      </div>
      <p style="font-size: 1rem; color: #2c2820; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Territory Occupancy</p>
    </a>

    <!-- First-year Survival -->
    <a href="research-survival" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1rem; width: 280px;">
      <div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 16px rgba(90,122,74,0.45))'; this.style.transform='translateY(-5px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/nestling.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
      </div>
      <p style="font-size: 1rem; color: #2c2820; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">First-year Survival</p>
    </a>

    <!-- Adult Turnover -->
    <a href="research-turnover" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1rem; width: 280px;">
      <div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 16px rgba(90,122,74,0.45))'; this.style.transform='translateY(-5px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/adult_DNA.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(2.0); transform-origin: center;">
      </div>
      <p style="font-size: 1rem; color: #2c2820; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Adult Turnover</p>
    </a>

  </div>

  <p style="text-align: center; margin: 0;">
    <a href="research" style="color: #5a7a4a; font-size: 0.95rem;">→ View all research projects</a>
  </p>

</div>
