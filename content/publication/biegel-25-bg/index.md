---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Unrecognised water limitation is a main source of uncertainty for models of
  terrestrial photosynthesis
subtitle: ''
summary: ''
authors:
- Samantha Biegel
- Konrad Schindler
- Benjamin D. Stocker
tags:
- FLUXNET
- GPP
- LSTM
- P-model
categories: []
date: '2025-12-01'
lastmod: 2025-12-01T08:30:21+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-12-01T07:30:21.462426Z'
publication_types:
- '2'
abstract: 'Quantification of environmental controls on ecosystem photosynthesis is
  essential to understand the impacts of climate change and extreme events on the
  carbon cycle and the provisioning of ecosystem services. Machine learning models
  have become popular for simulating ecosystem terrestrial photosynthesis because
  of their predictive skill, but often do not consider temporal dependencies in the
  data, even though process understanding suggests that these should exist. Here,
  we investigate how models that account for temporal structure impact the prediction
  of ecosystem photosynthesis. Using time-series measurements of ecosystem fluxes
  paired with measurements of meteorological variables from a network of globally
  distributed sites (N=104) and remotely sensed vegetation indices, we train three
  different models to predict ecosystem gross primary production (GPP): a mechanistic,
  theory-based photosynthesis model, a memoryless multilayer perceptron (MLP) and
  a recurrent neural network (Long Short-Term Memory, LSTM). Through comparisons of
  patterns in model error, we assess the ability of these models to predict GPP across
  a wide diversity of ecosystems and climates, and to account for temporal dependencies,
  with a focus on effects by low rooting zone moisture and freezing air temperatures.
  While both deep learning models outperform the mechanistic model, we find their
  overall performance is similar, with an R2 of 0.79 spatial out-of-sample predictions
  for both models. Overall, model skill is consistently good across moist sites with
  strong seasonality. During periods affected by temporal patterns such as drought
  and frost, the LSTM shows lower model error than the MLP as well as an LSTM with
  shuffled input, showing that there is an advantage from learned temporal dependencies.
  Generalisation patterns reveal that the LSTM tends to be more successful than the
  (time-agnostic) MLP in simulating GPP in dry environments. However, a large variability
  in model skill across relatively dry sites remained. This was not resolved by the
  inclusion of additional earth observation data, although this improved overall model
  performance. Insufficient information on the exposure and response to water stress
  and related effects on GPP appear to be dominant sources of error for modelling
  ecosystem fluxes across the globe. With the increasing frequency of hydroclimatic
  extreme events, effects of water limitation are expected to become more prevalent,
  which calls for models that better represent its impact on ecosystem function.'
publication: '*Biogeosciences*'
doi: 10.5194/bg-22-7455-2025
links:
- name: URL
  url: https://bg.copernicus.org/articles/22/7455/2025/
---
