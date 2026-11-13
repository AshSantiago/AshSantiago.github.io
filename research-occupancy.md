---
layout: single
title: "How do eagles respond to a drastically altered landscape?"
excerpt: "Territory Occupancy"
header:
  overlay_image: /assets/narrows_landscape.jpg
  overlay_filter: 0.5
  actions:
    - label: "Read the paper: Santiago et al. (2025)"
      url: "https://doi.org/10.1093/ornithapp/duaf054"
toc: true
toc_label: "On this page"
toc_sticky: true
---

[← Back to Research](/research)

## Shifting Landscape

Increasing frequency and severity of wildfires in the West has drastically altered many sagebrush-steppe ecosystems. Sagebrush communities are slow to recover after fires, whereas annual grasses, like cheatgrass (*Bromus tectorum*), grow back quickly, outcompete native shrubs, and create fuel and ignition points for fires to spread. This perpetuates the cycle of shrub loss and annual grass expansion and creates a feedback cycle:

1. Cheatgrass establishes in disturbed areas, creating ignition points and fuel for fires to spread.
2. Wildfires ignite more easily, spread faster, and burn more frequently than native plants can recover from.
3. Cheatgrass outcompetes native shrubs.
4. Shrub-reliant prey, like jackrabbits, ground squirrels, and other small mammals, decline as their habitat disappears.

For Golden Eagles, this cycle has bottom-up consequences as the prey they rely on lose the shrub communities that support them.

Golden eagles in southwestern Idaho are heavily tied to black-tailed jackrabbits (*Lepus californicus*), a prey species that relies on intact shrub cover to survive. But the sagebrush communities in southwestern Idaho have been greatly reduced because of fire and invasive annual grass expansion. If less shrub cover means fewer jackrabbits, what does this mean for eagles?

{% include figure image_path="/assets/grass-fire_cycle.png" alt="Annual grass-fire cycle diagram" caption="The annual grass–fire cycle." %}

## Territory Quality?

We used a multi-season Bayesian occupancy model with imperfect detection to evaluate how landscape characteristics within 36 historically occupied territories predicted whether the territory was occupied in a given year across a 36-year monitoring period.

Territory quality was assessed using three land cover covariates extracted from remotely sensed data:

- **Shrub Cover:** a proxy for habitat quality and prey availability
- **Annual Grass Cover:** an indicator of cheatgrass invasion and habitat degradation
- **Fire History:** years since last fire, capturing how recently and frequently a territory burned

{% include figure image_path="/assets/NCA_terr_buff_topo.png" alt="Map of shrub cover across eagle territories in 2022" caption="Shrub cover across the 36 Golden Eagle territories in the Morley Nelson Snake River Birds of Prey National Conservation Area, southwestern Idaho (2022)." %}

## Neighbor Density

In a degraded landscape where prey is scarce, eagles may need more space to meet their energetic needs, but their ability to expand depends on surrounding occupied territories.

Eagles can expand a territory they already occupy if there are no adjacent occupied territories or if a neighboring territory becomes vacant. A neighboring vacant territory may give the pair the opportunity to subsume it, increasing their nearby foraging range. But pairs surrounded by occupied territories on all sides have nowhere to expand, potentially pushing them out entirely. It is possible that the combination of degraded habitat and having nowhere to expand is causing territories to become vacant and remain vacant.

We evaluated conspecific neighbor density alongside land cover covariates to capture how eagles may cope with habitat loss.

{% include figure image_path="/assets/Occ_vac.png" alt="Map of territory occupancy" caption="Occupied territories (blue) and unoccupied territories (orange) across the study area." %}

## Occupancy Trends by Territory

Some territories have been consistently occupied for decades. Others went vacant years ago and never recovered. Territories that went vacant for five or more years tended to stay vacant. Some show a slow, steady decline. And others flicker between close to 0 and 1, likely reflecting the same pair nesting in two adjacent territories in different years.

{% include figure image_path="/assets/OccxTime_byTerr.png" alt="Individual territory occupancy over time" caption="Estimated occupancy probability for each of the 36 territories from 1986–2022." %}

## Declining Occupancy

The probability of occupancy at historically occupied breeding territories has dropped 25% over 36 years.

{% include figure image_path="/assets/occupancy_decline.png" alt="Overall occupancy trend over time" caption="Mean occupancy probability across all 36 territories from 1986–2022, with 95% credible interval." %}

## Potential Drivers of Occupancy Trends

Shrub cover and neighbor density emerged as the strongest predictors of territory occupancy. Shrub cover was positively associated with occupancy, while neighbor density had a strong negative effect, supporting the hypothesis that habitat degradation and spatial constraints are associated with occupancy trends.

{% include figure image_path="/assets/occupancy_covariates.png" alt="Covariate effects on occupancy" caption="The estimated effect of each landscape variable on territory occupancy. Points show the average estimate; bars show the range of plausible values. Effects that don't overlap zero are the most reliable." %}

**🌿 Shrub Cover**: strong positive effect  
Territories with more native shrubs were more likely to be occupied.
{: .notice--success}

**🦅 Neighbor Density**: strong negative effect  
Territories surrounded by more occupied neighbors were less likely to be occupied.
{: .notice--warning}

**🌾 Annual Grass Cover**: weak negative effect  
More cheatgrass was associated with lower occupancy, but the effect was small with high uncertainty.
{: .notice}

**🔥 Time Since Fire**: weak positive effect  
Territories that hadn't burned recently tended to have slightly higher occupancy, but the effect was uncertain.
{: .notice}

## Decline, Resilience, and What Comes Next

<div class="notice--info" markdown="1">
This research supports the idea that the carrying capacity for Golden Eagles in southwestern Idaho may be changing, with fewer pairs occupying the NCA and those that remain potentially holding larger, lower-quality territories.

But the story isn't only one of loss. Eagles are showing real resilience and adaptability by expanding into vacant neighboring territories, shifting between adjacent nesting areas year to year, and persisting in territories that appear to be low-quality. This behavioral flexibility buys time to understand the mechanisms behind the decline, assess population health, and develop targeted conservation strategies that have the greatest impact on population growth.

*Stay tuned! My dissertation research digs deeper into survival, population health, and what the future holds for Golden Eagles in southwestern Idaho.*
</div>

[← All Research](/research){: .btn .btn--inverse}
[Hatch-year Survival →](/research-survival){: .btn .btn--primary}
