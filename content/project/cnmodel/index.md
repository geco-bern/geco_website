---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Theory and data of carbon-nitrogen cycle interactions"
summary: "A stock-take of current modelling capabilities and a way forward with eco-evolutionary optimality theory."
authors: [Benjamin Stocker]
tags: []
categories: []
date: 2025-04-23T13:50:03+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### *How does nitrogen influence the global carbon cycle?*

Nitrogen is an essential nutrient for plants and is used both in photosynthesis enzymes and for building cell structures. Therefore, plant availability of nitrogen plays an important role in the global carbon cycle and its change under global warming and an increase in atmospheric CO<sub>2</sub>. For example, the question is whether and to what extent nitrogen availability limits the CO<sub>2</sub> fertilization of plant growth. Global models simulate these relationships and therefore require a solid understanding of relevant processes. In our review study (Stocker et al., 2024), we show (i) that these models simulate strongly divergent global carbon balances in recent decades (Fig. 1), (ii) that these divergences are related to different representations of carbon-nitrogen cycle interactions, and (iii) that theoretical foundations from evolutionary ecology enable more robust models that explain essential patterns from empirical analyses and experiments.

![TRENDY C sink](sink_trend_trendy.png "Temporal change in the global C sink over the years 1959-2020 from model simulations and observations (Obs.). Models are divided into model types that simulate carbon and nitrogen interactions (CN) and models that only simulate the carbon cycle (C). Model names are given in the legend. This figure shows that CN models diverge strongly in their simulation of the land carbon sink, while C models are relatively consistent with each other, but systematically overestimate the sink. Figure from Stocker et al. (2024).")

In another study (Stocker & Prentice, 2024), we show how these theoretical foundations can be implemented in a dynamic model of terrestrial carbon and nitrogen dynamics. The foundation of the model is (i) the acclimatization of photosynthesis to the abiotic environment (climate, CO<sub>2</sub>) and its implication for nitrogen demand, and (ii) the allocation of assimilated carbon for growth in aboveground biomass (stem, leaves) versus root growth. The model representation of allocation is based on the functional balance approach, which is dynamically simulated in the model as a function of nitrogen, light, and CO<sub>2</sub> availability. With these relatively simple basic assumptions, we can predict both the seasonal plant growth dynamics and the CO<sub>2</sub> and nitrogen balance of the ecosystem (Fig. 2), as well as the response of plants to experimentally manipulated CO<sub>2</sub> concentration and nitrogen fertilization. Thus, we provide a demonstration of how the core of global vegetation models can be formulated to more reliably simulate global changes in the carbon cycle and thus in the Earth system. 

![N sinks](n_sinks_sources.png "")
![C sinks](c_sinks_sources.png "Modeled seasonal plant growth dynamics and the C and nitrogen (N) balance of an ecosystem. Figure from Stocker & Prentice (2024).")

#### References

Stocker, B. D., Dong, N., Perkowski, E. A., Schneider, P. D., Xu, H., de Boer, H. J., Rebel, K. T., Smith, N. G., Van Sundert, K., Wang, H., Jones, S. E., Prentice, I. C., and Harrison, S. P.: Empirical evidence and theoretical understanding of ecosystem carbon and nitrogen cycle interactions, *New Phytologist*, n/a, https://doi.org/10.1111/nph.20178, n.d.

Stocker, B. D. and Prentice, I. C.: CN-model: A dynamic model for the coupled carbon and nitrogen cycles in terrestrial ecosystems, *biorxiv*, https://doi.org/10.1101/2024.04.25.591063, 28 April 2024. [pre-print]