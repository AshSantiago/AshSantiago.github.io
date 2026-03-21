---
layout: default
title: Home
---

<!-- Full-viewport hero with text overlay -->
<div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; height: 100vh; min-height: 600px; overflow: hidden; display: flex; align-items: flex-end; margin-bottom: 0;">
  <img src="assets/landscape.jpg" alt="Sagebrush steppe landscape"
       style="position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; object-position: center 40%;"
       onerror="this.parentElement.style.background='#3d5c30'; this.style.display='none';">
  <div style="position: absolute; inset: 0; background: linear-gradient(to top, rgba(30,40,20,0.75) 0%, rgba(30,40,20,0.3) 40%, transparent 70%);"></div>
  <div style="position: relative; z-index: 2; padding: 4rem 6rem; width: 100%;">
    <p style="font-family: 'Lora', serif; font-size: 0.85rem; letter-spacing: 0.2em; text-transform: uppercase; color: rgba(220,235,210,0.85); margin-bottom: 0.8rem;">Ecology, Evolution, & Behavior PhD Student · Boise State University · Raptor Research Center</p>
    <h1 style="font-family: 'Playfair Display', serif; font-size: 4.5rem; color: #f7f3ee; margin: 0 0 1rem; line-height: 1.05; text-shadow: 0 2px 20px rgba(0,0,0,0.3);">Ashley Santiago</h1>
  </div>
</div>

<!-- Bio strip — full width, two columns -->
<div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; background: #f0f4ec; padding: 5rem 6rem; display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center; margin-bottom: 0;">
  <div>
    <p style="font-size: 1.05rem; line-height: 1.85; color: #6b6259; margin-bottom: 1.5rem;">
           I am currently studying Golden Eagle ecology, survival, and population dynamics, combining field ecology with 
      statistical modeling and novel genomic approaches to understand the potential drivers of population decline and inform 
      conservation strategies. I work in the <a href="https://www.heathlab.com" target="_blank">Heath Lab</a> at Boise State University.
    </p>
  </div>
  <div style="display: flex; justify-content: center;">
    <img src="assets/profile.jpg" alt="Ashley Santiago"
         style="width: 380px; height: 480px; object-fit: cover; object-position: center top; border-radius: 4px; box-shadow: 8px 8px 32px rgba(44,40,32,0.18);">
  </div>
</div>

<!-- Research section — dark background, full width -->
<div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; background: #2c3828; padding: 5rem 6rem; margin-bottom: 0;">
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; align-items: end; margin-bottom: 3.5rem;">
    <h2 style="font-size: 2rem; color: #f0f4ec; margin: 0; line-height: 1.2;">Research</h2>
    <p style="font-size: 1.05rem; line-height: 1.8; color: rgba(220,235,210,0.8); margin: 0;">
      My work integrates long-term field data, statistical modeling, and genomics to understand raptor population dynamics and inform conservation management.
    </p>
  </div>

  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 2rem;">

    <!-- Territory Occupancy -->
    <a href="research-occupancy" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1.2rem;">
      <div style="width: 100%; aspect-ratio: 1; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 20px rgba(90,122,74,0.6))'; this.style.transform='translateY(-6px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/occupancy.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
      </div>
      <div style="text-align: center;">
        <p style="font-size: 0.75rem; letter-spacing: 0.15em; text-transform: uppercase; color: #85a870; margin: 0 0 0.3rem;">Territory Ecology</p>
        <p style="font-size: 1.05rem; color: #f0f4ec; font-family: 'Playfair Display', serif; margin: 0; font-weight: 600;">Territory Occupancy</p>
      </div>
    </a>

    <!-- First-year Survival -->
    <a href="research-survival" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1.2rem;">
      <div style="width: 100%; aspect-ratio: 1; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 20px rgba(90,122,74,0.6))'; this.style.transform='translateY(-6px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/nestling.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
      </div>
      <div style="text-align: center;">
        <p style="font-size: 0.75rem; letter-spacing: 0.15em; text-transform: uppercase; color: #85a870; margin: 0 0 0.3rem;">Survival Analysis</p>
        <p style="font-size: 1.05rem; color: #f0f4ec; font-family: 'Playfair Display', serif; margin: 0; font-weight: 600;">First-year Survival</p>
      </div>
    </a>

    <!-- Adult Turnover -->
    <a href="research-turnover" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 1.2rem;">
      <div style="width: 100%; aspect-ratio: 1; border-radius: 50%; overflow: hidden; transition: all 0.25s;"
           onmouseover="this.style.filter='drop-shadow(0 8px 20px rgba(90,122,74,0.6))'; this.style.transform='translateY(-6px)'"
           onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
        <img src="/assets/adult_DNA.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(2.0); transform-origin: center;">
      </div>
      <div style="text-align: center;">
        <p style="font-size: 0.75rem; letter-spacing: 0.15em; text-transform: uppercase; color: #85a870; margin: 0 0 0.3rem;">Population Genomics</p>
        <p style="font-size: 1.05rem; color: #f0f4ec; font-family: 'Playfair Display', serif; margin: 0; font-weight: 600;">Adult Turnover</p>
      </div>
    </a>

  </div>

  <div style="text-align: center; margin-top: 3rem;">
    <a href="research" style="display: inline-block; border: 1.5px solid rgba(220,235,210,0.4); color: rgba(220,235,210,0.85); padding: 0.65rem 2rem; border-radius: 3px; font-family: 'Lora', serif; font-size: 0.88rem; letter-spacing: 0.08em; text-transform: uppercase; transition: all 0.2s;"
       onmouseover="this.style.borderColor='#85a870'; this.style.color='#c8dabb'"
       onmouseout="this.style.borderColor='rgba(220,235,210,0.4)'; this.style.color='rgba(220,235,210,0.85)'">View All Research →</a>
  </div>
</div>
