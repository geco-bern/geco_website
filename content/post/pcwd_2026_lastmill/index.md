---
title: "Is the European 2026 drought unprecedented in the last millennium?"
subtitle: ""
summary: ""
authors: [Benjamin Stocker]
tags: [drought]
categories: []
date: 2026-08-26T16:47:45+02:00
lastmod: 2026-08-26T16:47:45+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Pasture in Les Prés d'Orvin, Switzerland, July 2026. Image credit: Benjamin Stocker"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

[Patricia Helpap](https://geco-group.org/author/patricia-helpap/) recently published her Master thesis work in *AGU Advances* ([Helpap et al., 2026](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2026AV002536)). She contrasted the droughts of the recent past (2000-2024) versus an extended context, covering the past 600 years and the unforced atmospheric variability, represented by an ensemble of twenty 600-year simulations that together span the range of possible "realisations" of the inherently chaotic climate. This asked the question of whether recent droughts are unprecedented and beyond the range of variability estimated for the past. She found that (up to 2024), droughts of the 21st century have not yet exceeded the full range of this extended reference in many regions across the globe. Individual years showed up in individual model simulations (ensemble members) where the drought magnitude exceeded even 21st century droughts. This partly reflects the nature of statistics: the longer you wait and the more realisations of the inherently chaotic climate system you consider, the higher the probability that you'll find an individual year showing an even stronger drought than what was recorded by climate reanalysis for the past decades. One novelty of her study was that she extended this reference massively compared to what is commonly done when considering a restricted historical reference, commonly based on climate reanalysis and other climate reconstructions of the past 50-150 years. 

But that's only part of the story. The other part is that we found a clear shift of the distribution of drought magnitudes and extremes in most regions globally. Even if it hasn't shown up in the recent past, the probability for regions to experience extreme droughts today has shifted and is now higher than ever before in the last 600 years in most regions globally. 

So far so (not so) good. But then came the summer of 2026. In Europe, we have experienced a level of dryness many of us (all of us?) cannot remember to have ever experienced before. Trees and grasslands turned brown all around, agriculture is in a crisis, emergency relief was triggered to safe livestock and harvests. With my research group, we have pulled several different data types together to provide a continuous monitoring of the drought situation in the [Bern Drought Monitor](https://geco-bern.github.io/bern_drought_monitor/). This showed what we felt and saw with data: The magnitude of water deficits in 2026 has moved far beyond what was ever recorded in the past 45 years. The 2026 climate extreme event unfolded while Patricia's paper was published. And the question was obvious: would her fresh results hold up against an updated analysis that included data 2026 in the analysis? (Her analysis included years only up to 2024.)

This is why we re-opened the case and ran her code again with updated climate reanalysis (ERA5-Land), contrasted against the same multi-centennial reference as she used in her study and with the same averaging across the region 'Western Central Europe' (WCE), which spans from France to Ukraine and the Baltic states. The results show a nuanced picture. 

![summer change in precipitation](PCWD_WCE.png "Annual maximum Potential Cumulative Water Deficit (PCWD) time series and distributions. (left) PCWD time series from 1420 to 2024 for WCE (Western Central Europe IPCC region). Thin light blue lines denote individual simulation ensemble members. Dark blue lines denote the ensemble mean. Black line shows the 25‐year rolling mean of the ensemble mean. Red line denotes ERA5‐Land PCWD for 1975–2026. Horizontal blue line shows the maximum PCWD value across all simulation ensemble members. The horizontal red line shows the 2026 value. (right) Distribution of the PCWD from the simulations (blue) and climate reanalysis (red) for WCE.")

For the WCE region, 2026 doesn't stand out as a record drought year. The Potential Cumulative Water Deficit (PCWD, see explanation in German [here](https://geco-bern.github.io/bern_drought_monitor/#potenzielles-kumulatives-wasserdefizit-pcwd) and in English [here](https://geco-bern.github.io/cwd/index.html)) of 2018 remains the highest ever recorded based on climate reanalysis data (ERA5-Land). Also the twenty ensemble simulations of the past climate, sampling a good portion of viable realisations of the climate variability, given reconstructed boundary conditions (greenhouse gases, insolation, volcanic activity, sea surface temperatures) did not produce clearly larger events in the past 600 years. (In fact, 1598 and 1427 did produce slightly higher PCWD in one of the ensemble members respectively with 171 mm and 170.1 mm, compared to the ERA5-Land-based 2018 estimate of 170.0 mm). Of course, the perhaps most striking feature for the WCE region is the systematic and rapidly increasing trend of PCWD over the past decades as recorded by climate reanalysis (red line), indicating a continuous shift towards stronger droughts in Europe.

The reason for the result of 2026 not coming out on top, which obviously doesn't align with our (Switzerland-centred) perception of this year's drought is beause the eastern part of the large WCE region wasn't extremely dry this year. We therefore did the same analysis also for just Switzerland. Note however, that the analysis was done here at a spatial grid of 1.8 degrees (about 180 km). One gridcell hence covers much of Switzerland and the resulting PCWD includes regions that varied in dryness in 2026, with compensating contributions from the extremely dry lowlands and the less extremely dry Alps region (see also [here](https://geco-bern.github.io/bern_drought_monitor/#r%C3%A4umliche-darstellung-des-aktuellen-pcwd)). Nevertheless, 2026 showed up as the strongest ever recorded drought among the years covered by ERA5-Land. A small number of individual years showed even higher PCWD in the twenty simulation ensemble members for the past 600 years. Strictly speaking, the 2026 did therefore not emerge as *unprecedented* against this (synthetic) reference. Yet, it stood out as a rare extreme. In numbers, the 2026 PCWD corresponds to the 99.8% percentile. Roughly speaking and in simplified terms, this means that a drought like the one of 2026 can be expected to happen about twice every 1000 years if we were still living in the pre-anthropogenic climate-change world. 

![summer change in precipitation](PCWD_CHE.png "Annual maximum PCWD time series and distributions. (left) PCWD time series from 1420 to 2024 for Switzerland (values extracted from the corresopnding gridcell). Thin light blue lines denote individual simulation ensemble members. Dark blue lines denote the ensemble mean. Black line shows the 25‐year rolling mean of the ensemble mean. Red line denotes ERA5‐Land PCWD for 1975–2026. Horizontal blue line shows the maximum PCWD value across all simulation ensemble members. The horizontal red line shows the 2026 value. (right) Distribution of the PCWD from the simulations (blue) and climate reanalysis (red) for Switzerland.")

Unfortunately, we don't. The statistics of drought are shifting as Patricia showed in her paper (Helpap et al., 2026) and the probability to be hit again by a drought of 2026-level or worse is increasing from year to year as global warming progresses and greenhouse gas emissions are not reduced to net-zero.

## References

Helpap, P., Brönnimann, S., Hand, R., Franke, J., Raible, C. C., and Stocker, B. D.: Are Modern Droughts Unprecedented?, *AGU Advances*, 7, e2026AV002536, https://doi.org/10.1029/2026AV002536, 2026.

