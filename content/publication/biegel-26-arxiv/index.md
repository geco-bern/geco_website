---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Country-wide, high-resolution monitoring of forest browning with Sentinel-2
subtitle: ''
summary: ''
authors:
- Samantha Biegel
- David Brüggemann
- Francesco Grossi
- Michele Volpi
- Konrad Schindler
- Benjamin D. Stocker
tags:
- NDVI
- Computer Science - Computer Vision and Pattern Recognition
- Sentinel-2
- anomaly detection
- Statistics - Applications
categories: []
date: '2026-04-01'
lastmod: 2026-08-12T22:38:08+02:00
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
publishDate: '2026-08-12T20:38:07.912040Z'
publication_types:
- '0'
abstract: Natural and anthropogenic disturbances are impacting the health of forests
  worldwide. Monitoring forest disturbances at scale is important to inform conservation
  efforts. Here, we present a scalable approach for country-wide mapping of forest
  greenness anomalies at the 10 m resolution of Sentinel-2. Using relevant ecological
  and topographical context and an established representation of the vegetation cycle,
  we learn a predictive quantile model of the normalised difference vegetation index
  (NDVI) derived from Sentinel-2 data. The resulting expected seasonal cycles are
  used to detect NDVI anomalies across Switzerland between April 2017 and August 2025.
  Goodness-of-fit evaluations show that the conditional model explains 65% of the
  observed variations in the median seasonal cycle. The model consistently benefits
  from the local context information, particularly during the green-up period. The
  approach produces coherent spatial anomaly patterns and enables country-wide quantification
  of forest browning. Case studies with independent reference data from known events
  illustrate that the model reliably detects different types of disturbances.
publication: '*arXiv*'
doi: 10.48550/arXiv.2604.02074
links:
- name: URL
  url: http://arxiv.org/abs/2604.02074
---
