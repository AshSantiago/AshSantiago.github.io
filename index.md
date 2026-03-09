---
layout: default
title: Home
---

<!-- Landscape Hero Banner -->
<div style="width: 100%; height: 380px; overflow: hidden; border-radius: 8px; margin-bottom: 2.5rem; position: relative;">
  <img src="assets/landscape.jpg" alt="Sagebrush steppe landscape"
       style="width: 100%; height: 100%; object-fit: cover; object-position: center 40%;"
       onerror="this.parentElement.style.background='#a8b89a'; this.style.display='none';">
  <div style="position: absolute; inset: 0; background: linear-gradient(to top, rgba(44,40,32,0.35) 0%, transparent 60%);"></div>
</div>

<!-- Profile photo + Bio -->
<div style="max-width: 720px; margin: 0 auto 2.5rem; display: flex; align-items: flex-start; gap: 2rem;">
  <img src="assets/profile.jpg" alt="Ashley Santiago"
       style="width: 140px; height: 140px; object-fit: cover; object-position: center top; border-radius: 50%; flex-shrink: 0; box-shadow: 3px 3px 14px rgba(74,63,53,0.15); border: 3px solid #dde6d5;">
  <div>
    <h1 style="margin-top: 0.2rem; margin-bottom: 0.3rem;">Ashley Santiago</h1>
    <p style="margin: 0 0 0.8rem; color: #6b6259; font-style: italic; font-size: 0.95rem;">Ph.D. Student · Ecology, Evolution, and Behavior · Boise State University</p>
    <p style="font-size: 0.97rem; line-height: 1.8; margin: 0;">
      I am studying <strong>Golden Eagle ecology, survival, and population dynamics</strong>, 
      combining field ecology with statistical modeling and novel genomic approaches to understand 
      the potential drivers of population decline and inform conservation strategies.
      I work in the <a href="https://www.heathlab.com" target="_blank">Heath Lab</a> at Boise State University.
    </p>
  </div>
</div>

<hr style="border: none; border-top: 1px solid #dde6d5; margin: 0 auto 2.5rem; max-width: 720px;">

<!-- Research Preview -->
<div style="max-width: 720px; margin: 0 auto 2.5rem;">
  <h2 style="font-size: 1.25rem; margin-bottom: 1.2rem;">Research</h2>
  <p style="font-size: 1rem; line-height: 1.75; margin-bottom: 1.5rem;">My work integrates field data, statistical modeling, and genomics to understand raptor population dynamics and inform conservation management.</p>

  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; margin-bottom: 1.5rem;">

    <a href="research-occupancy" style="text-decoration: none;">
      <div style="background: #f0f4ec; border: 1px solid #dde6d5; border-top: 3px solid #7a8c6e; border-radius: 6px; padding: 1.1rem 1.2rem;"
           onmouseover="this.style.boxShadow='0 4px 16px rgba(74,63,53,0.12)'; this.style.transform='translateY(-2px)'"
           onmouseout="this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <p style="font-size: 0.75rem; letter-spacing: 0.12em; text-transform: uppercase; color: #7a8c6e; margin: 0 0 0.4rem;">Territory Occupancy</p>
        <p style="font-size: 0.88rem; color: #4a3f35; margin: 0; line-height: 1.5;">Landscape drivers of long-term changes in golden eagle territory use in southwestern Idaho.</p>
      </div>
    </a>

    <a href="research-survival" style="text-decoration: none;">
      <div style="background: #f0f4ec; border: 1px solid #dde6d5; border-top: 3px solid #7a8c6e; border-radius: 6px; padding: 1.1rem 1.2rem;"
           onmouseover="this.style.boxShadow='0 4px 16px rgba(74,63,53,0.12)'; this.style.transform='translateY(-2px)'"
           onmouseout="this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <p style="font-size: 0.75rem; letter-spacing: 0.12em; text-transform: uppercase; color: #7a8c6e; margin: 0 0 0.4rem;">Juvenile Survival</p>
        <p style="font-size: 0.88rem; color: #4a3f35; margin: 0; line-height: 1.5;">Age-specific survival modeling using telemetry to identify stressors on first-year eagles.</p>
      </div>
    </a>

    <a href="research-turnover" style="text-decoration: none;">
      <div style="background: #f0f4ec; border: 1px solid #dde6d5; border-top: 3px solid #7a8c6e; border-radius: 6px; padding: 1.1rem 1.2rem;"
           onmouseover="this.style.boxShadow='0 4px 16px rgba(74,63,53,0.12)'; this.style.transform='translateY(-2px)'"
           onmouseout="this.style.boxShadow='none'; this.style.transform='translateY(0)'">
        <p style="font-size: 0.75rem; letter-spacing: 0.12em; text-transform: uppercase; color: #7a8c6e; margin: 0 0 0.4rem;">Conservation Genomics</p>
        <p style="font-size: 0.88rem; color: #4a3f35; margin: 0; line-height: 1.5;">Using genomic tools to assess population connectivity and health in a declining raptor.</p>
      </div>
    </a>

  </div>

  <p style="font-size: 0.9rem; margin: 0;">
    <a href="research" style="color: #7a8c6e;">→ View all research projects</a>
  </p>
</div>
