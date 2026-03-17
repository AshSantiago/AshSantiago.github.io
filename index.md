---
layout: default
title: Home
---

<!-- Full-bleed landscape banner -->
<div style="width: 100vw; position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; height: 420px; overflow: hidden; margin-bottom: 3rem;">
  <img src="assets/landscape.jpg" alt="Sagebrush steppe landscape"
       style="width: 100%; height: 100%; object-fit: cover; object-position: center 40%;"
       onerror="this.parentElement.style.background='#a8b89a'; this.style.display='none';">
  <div style="position: absolute; inset: 0; background: linear-gradient(to top, rgba(44,40,32,0.3) 0%, transparent 60%);"></div>
</div>

<!-- Profile photo + Bio -->
<div style="max-width: 900px; margin: 0 auto 2.5rem; display: flex; align-items: flex-start; gap: 2rem;">
  <img src="assets/profile.jpg" alt="Ashley Santiago"
       style="width: 250px; height: 250px; object-fit: cover; object-position: center top; border-radius: 50%; flex-shrink: 0; box-shadow: 3px 3px 14px rgba(74,63,53,0.15); border: 3px solid #dde6d5;">
  <div>
    <h1 style="margin-top: 0.2rem; margin-bottom: 0.3rem;">Ashley Santiago</h1>
    <p style="margin: 0 0 0.8rem; color: #6b6259; font-style: italic; font-size: 1.05rem;">Ph.D. Student · Ecology, Evolution, and Behavior · Boise State University</p>
    <p style="font-size: 1.25rem; line-height: 1.8; margin: 0;">
      I am studying <strong>Golden Eagle ecology, survival, and population dynamics</strong>, combining field ecology with 
      statistical modeling and novel genomic approaches to understand the potential drivers of population decline and inform 
      conservation strategies.I work in the <a href="https://www.heathlab.com" target="_blank">Heath Lab</a> at Boise State University.
    </p>
  </div>
</div>

<hr style="border: none; border-top: 1px solid #dde6d5; margin: 0 auto 2.5rem; max-width: 720px;">

<!-- Research circles -->
<div style="max-width: 900px; margin: 0 auto 2.5rem;">
  <h2 style="font-size: 1.45rem; margin-bottom: 0.6rem;">Research</h2>
  <p style="font-size: 1rem; line-height: 1.75; margin-bottom: 2rem;">My work integrates field data, statistical modeling, and genomics to understand raptor population dynamics and inform conservation management.</p>

  <div style="display: flex; justify-content: center; gap: 2.5rem; flex-wrap: wrap; margin-bottom: 1.8rem;">

   <!-- Territory Occupancy -->
<a href="research-occupancy" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 280px;">
<div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.2s;"
     onmouseover="this.style.filter='drop-shadow(0 6px 10px rgba(122,140,110,0.5))'; this.style.transform='translateY(-4px)'"
     onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
    <img src="/assets/occupancy.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
  </div>
  <p style="font-size: 1.1rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Territory Occupancy</p>
</a>

<!-- First-year Survival -->
<a href="research-survival" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 280px;">
<div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.2s;"
     onmouseover="this.style.filter='drop-shadow(0 6px 10px rgba(122,140,110,0.5))'; this.style.transform='translateY(-4px)'"
     onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
    <img src="/assets/nestling.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(1.2); transform-origin: center;">
  </div>
  <p style="font-size: 1.1rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">First-year Survival</p>
</a>

<!-- Adult Turnover -->
<a href="research-turnover" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 280px;">
<div style="width: 260px; height: 260px; border-radius: 50%; overflow: hidden; transition: all 0.2s;"
     onmouseover="this.style.filter='drop-shadow(0 6px 10px rgba(122,140,110,0.5))'; this.style.transform='translateY(-4px)'"
     onmouseout="this.style.filter='none'; this.style.transform='translateY(0)'">
    <img src="/assets/adult_DNA.png" style="width: 100%; height: 100%; object-fit: cover; display: block; transform: scale(2.0); transform-origin: center;">
  </div>
  <p style="font-size: 1.1rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Adult Turnover</p>
</a>
  </div>

  <p style="font-size: 1.1rem; margin: 0; text-align: center;">
    <a href="research" style="color: #7a8c6e;">→ View all research projects</a>
  </p>
</div>
