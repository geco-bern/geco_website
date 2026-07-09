---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "SCALE-UP (SNF Lead Agency)"
summary: "Understanding VPD impacts on forests across scales to advance the next generation of Earth-system models."
authors: [Benjamin Stocker]
tags: []
categories: []
date: 2026-06-01T13:50:03+02:00

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

**Understanding VPD impacts on forests across scales to advance the next generation of Earth-system models.**

## Overview

Vapor pressure deficit (VPD) is rising globally, but its impacts on foliar gas exchange, tree growth, mortality, and forest carbon and water fluxes are poorly known. Fundamental questions remain regarding how VPD affects different species and how these effects are influenced by concurrent soil drought (i.e., low precipitation and soil moisture) and plant acclimation across time scales, from minutes to decades, and spatial scales, from individual leaves to whole ecosystems. These uncertainties undermine confidence in model projections of future vegetation dynamics and carbon cycle changes, making it difficult to accurately predict climate impacts on ecosystems. As a result, our ability to develop and implement climate-smart management practices that could mitigate these impacts is significantly hindered, leaving forests vulnerable to the accelerating effects of rising VPD. Using a cross-scale approach, SCALE-UP will unravel (1) the mechanisms underlying the variation of VPD impacts across species on gas exchange, growth, mortality, and ecosystem-scale carbon and water fluxes, (2) the interaction of these responses with soil drought, (3) the potential for acclimation to rising VPD and its role in mitigating impacts of extreme events, and (4) the development of mechanistic insights and predictive models to understand and project VPD effects on forests at multiple scales.

## Basics

- Funding agency: US NSF and Swiss NSF (Lead Agency)
- Start (Swiss partners): 1 October 2026
- Duration: 4 years
- Volume (Bern): 2 PhD, 1 Postdoc

## PIs

- **Charlotte Grossiord** (EPFL Lausanne)
- **Nate McDowell** (PNNL, USA)
- **Matt Dannenberg** (University of Iowa, USA)
- **Benjamin Stocker** (Bern)

**Collaborators**

- Marcus Schaub (WSL Birmensdorf, Switzerland)
- Henry Adams (Washington State University, USA) 
- Kim Novick (Indiana University, USA)

## Objectives

- **O1: Link traits to VPD responses.** How leaf and whole-plant traits explain species differences in gas exchange, growth, and mortality under VPD.
- **O2: Test soil moisture interactions.** How soil drought changes VPD effects.
- **O3: Quantify acclimation.** Whether acclimation reduces VPD sensitivity.
- **O4: Scale to ecosystems.** Net effects on GPP, growth, mortality, and community composition (past and future).

![UP-SCALE project overview](upscale_overview.png "Overview of work packages in project UP-SCALE.") 

## Work plan

### WP1

- **Scope**: Leaf exchange as influenced by plant hydraulic traits.
- **Hypothesis**: Less sensitive response to elevated VPD and low soil moisture for species with traits adapted to dry conditions (e.g., less vulnerable xylem and lower leaf area).
- **Approach**: Seedling and ecosystem VPD manipulation (VPDrought, Pfynwald) experiments.

### WP2

- **Scope**: Tree growth and mortality as influenced by plant hydraulic traits
- **Hypothesis**: Growth and mortality are driven by the interplay of stomatal responses to VPD and soil moisture, plant hydraulics, and a tree’s C balance and allocation.
- **Approach**: Experiments (as in WP1)

### WP3

- **Scope**: Tree growth and mortality trends and variability across the northern extratropics
- **Hypothesis**: Less sensitive growth response to VPD and soil moisture in drought-adapted species, and in (within-species) populations acclimated to dry conditions.
- **Approach:** High-frequency dendrometer data, International Tree Ring Data Bank, forest inventory data
    - Subdaily data for disentangling VPD-soil moisture effects
    - Forest inventory data for stand-level productivity estimation from tree-ring data

### WP4

- **Scope**: Modelling of VPD impacts on historical and future ecosystem-scale growth, mortality, and GPP, isolating effects of soil droughts, acclimation, and community composition shifts.
- **Hypothesis**: A representation of species’ (acclimating) hydraulic traits improves simulation of leaf gas exchange, ecosystem fluxes, growth, and mortality to elevated VPD (and low soil moisture).
    - Climate change projection: Acclimation and species composition shifts reduces sensitivity to drought (high VPD and low soil moisture), but imply reduced C uptake during non-drought conditions. This dampens C cycle variability, but at lower C cycling rates.
- **Approach**: Integrating a hydraulics-explicit representation of optimal photosynthesis, transpiration, and their acclimation (P-hydro, [Joshi et al. 2022](https://doi.org/10.1038/s41477-022-01244-5)) into a forest demography model ([BiomeEP](https://geco-bern.github.io/rsofun/articles/biomee_use.html)). Model development for optimal allocation. Model calibration and evaluation with data from all scales (plant traits, ecosystem and seedling experiments, ecosystem fluxes, sap flow, leaf water potentials, dendrometer, tree-ring widths, forest inventories). Past-to-future simulations separating effects of long-term trends in VPD, CO2, community shifts, and acclimation.
