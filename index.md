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
  <h2 style="font-size: 1.4rem; margin-bottom: 0.6rem;">Research</h2>
  <p style="font-size: 1.3rem; line-height: 1.75; margin-bottom: 2rem;">My work integrates field data, statistical modeling, and genomics to understand raptor population dynamics and inform conservation management.</p>

  <div style="display: flex; justify-content: center; gap: 2.5rem; flex-wrap: wrap; margin-bottom: 1.8rem;">

    <!-- Territory Occupancy -->
    <a href="research-occupancy" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 160px;">
      <div style="width: 140px; height: 140px; border-radius: 50%; background: #dde6d5; border: 3px solid #a8b89a; display: flex; align-items: center; justify-content: center; transition: all 0.2s;"
           onmouseover="this.style.borderColor='#7a8c6e'; this.style.boxShadow='0 6px 20px rgba(122,140,110,0.25)'; this.style.transform='translateY(-4px)'"
           onmouseout="this.style.borderColor='#a8b89a'; this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <svg width="52" height="52" viewBox="0 0 24 24" fill="none" stroke="#7a8c6e" stroke-width="1.2" xmlns="http://www.w3.org/2000/svg">
          <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/>
        </svg>
      </div>
      <p style="font-size: 1.2rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Territory Occupancy</p>
    </a>

    <!-- First-year Survival -->
    <a href="research-survival" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 160px;">
      <div style="width: 140px; height: 140px; border-radius: 50%; background: #dde6d5; border: 3px solid #a8b89a; display: flex; align-items: center; justify-content: center; transition: all 0.2s;"
           onmouseover="this.style.borderColor='#7a8c6e'; this.style.boxShadow='0 6px 20px rgba(122,140,110,0.25)'; this.style.transform='translateY(-4px)'"
           onmouseout="this.style.borderColor='#a8b89a'; this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <svg width="52" height="52" viewBox="0 0 24 24" fill="none" stroke="#7a8c6e" stroke-width="1.2" xmlns="http://www.w3.org/2000/svg">
          <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/>
        </svg>
      </div>
      <p style="font-size: 1.2rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">First-year Survival</p>
    </a>

    <!-- Adult Turnover -->
    <a href="research-turnover" style="text-decoration: none; display: flex; flex-direction: column; align-items: center; gap: 0.8rem; width: 160px;">
      <div style="width: 140px; height: 140px; border-radius: 50%; background: #dde6d5; border: 3px solid #a8b89a; display: flex; align-items: center; justify-content: center; transition: all 0.2s;"
           onmouseover="this.style.borderColor='#7a8c6e'; this.style.boxShadow='0 6px 20px rgba(122,140,110,0.25)'; this.style.transform='translateY(-4px)'"
           onmouseout="this.style.borderColor='#a8b89a'; this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <!-- Clean DNA helix icon -->
    <svg width="44" height="56" viewBox="0 0 44 56" fill="none" stroke="#7a8c6e" stroke-width="1.5" stroke-linecap="round" xmlns="http://www.w3.org/2000/svg">
      <!-- Left strand -->
      <path d="M10 2 C10 12, 34 16, 34 28 C34 40, 10 44, 10 54"/>
      <!-- Right strand -->
      <path d="M34 2 C34 12, 10 16, 10 28 C10 40, 34 44, 34 54"/>
      <!-- Rungs -->
      <line x1="13" y1="10" x2="31" y2="13"/>
      <line x1="10" y1="20" x2="34" y2="20"/>
      <line x1="10" y1="28" x2="34" y2="28"/>
      <line x1="10" y1="36" x2="34" y2="36"/>
      <line x1="13" y1="43" x2="31" y2="46"/>
    </svg>
      </div>
      <p style="font-size: 1.2rem; color: #4a3f35; font-family: 'Lora', serif; margin: 0; font-weight: 600; text-align: center;">Adult Turnover</p>
    </a>

  </div>

  <p style="font-size: 1.2rem; margin: 0; text-align: center;">
    <a href="research" style="color: #7a8c6e;">→ View all research projects</a>
  </p>
</div>
