---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Controls on leaf N and P"
summary: "Identifying global controls and spatial upscaling"
authors: [Benjamin Stocker]
tags: []
categories: []
date: 2025-04-22T13:50:03+02:00

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

### **(How) do environmental factors and species affiliation influence nitrogen (N) and phosphorus (P) concentrations in plant leaves?**

A widespread assumption is that the nutrient concentration of leaves is mainly determined by species affiliation - a concept known as the “biogeochemical niche hypothesis”. This hypothesis assumes that each plant species occupies a fixed biogeochemical niche with specific N:P ratios. Our study (Tian et al., 2024) challenges this assumption by analyzing the influence of environmental factors on leaf nutrient composition using various statistical and machine learning-based models.
 
![Random Forest vs. Linear Mixed Effects model](leafp_lmm_rf.png "Proportion of explained variation (*R*<sup>2</sup>) of environmental factors (Environment) and species identity, estimated with different model types (LMM: Linear Mixed Effects Models, RF: Random Forest).") 

About half of the total variation in leaf N and P and in the N:P ratio occurs within species, while environmental variables explain 29 % of the variation in leaf N, 31 % in leaf P and 22 % in the N:P ratio. Nitrogen deposition, atmospheric CO<sub>2</sub> concentrations and the temperature of the coldest month are particularly significant. Random forest models identified environmental factors as significant drivers of within-species variation, while linear mixed effects models largely failed to detect these effects. Many species show a high plasticity in their leaf nutrient composition along environmental gradients, indicating a flexible adaptation to different environmental conditions. The results of the study suggest that environmental factors play as important a role as phylogenetic affiliation in determining leaf nutrient composition. We also show that previous interpretations of the data were based on limited statistical methods. This challenges the previous assumption of a fixed biogeochemical niche and emphasizes the importance of phenotypic plasticity of plants.

#### Reference

Tian, D., Yan, Z., Schmid, B., Kattge, J., Fang, J., and Stocker, B. D.: Environmental versus phylogenetic controls on leaf nitrogen and phosphorous concentrations in vascular plants, *Nature Communications*, 15, 5346, https://doi.org/10.1038/s41467-024-49665-4, 2024.