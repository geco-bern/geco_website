---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Greenness of Swiss Forests"
summary: "Anomaly detection of the “greenness” of forests in Switzerland."
authors: ["Samantha Biegel","Benjamin Stocker"]
tags: []
categories: []
date: 2024-02-19T13:50:03+02:00

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

Recent extreme droughts have caused significant damage to forests across Switzerland and neighbouring regions. Identifying where and when climate extremes impact forest health is crucial for understanding their severity and developing early-warning systems. Remote sensing offers a valuable tool for detecting vegetation stress, as drought-induced tree mortality and premature defoliation appear as negative anomalies (browning) in vegetation indices such as NDVI. However, reliably identifying these anomalies in large, noisy Earth Observation (EO) datasets remains a major challenge. Additionally, distinguishing drought-related browning from other disturbances like late frost, deforestation, or storms requires additional advancements.

![](dimpeo.png) 
 
This project focuses on developing robust anomaly detection methods for high-resolution (20 m) Sentinel-2 EO time series data to map and quantify browning impacts on Swiss forests. We have developed two complementary approaches for detecting NDVI anomalies: a neural network-based method and a quantile random forest model. Both methods estimate a normal NDVI range by accounting for seasonal, spatial, and environmental variability, allowing us to flag pixels with significant deviations. One of the approaches has been deployed in a web application to provide a user-friendly interface for visualising detected anomalies across Switzerland.
 
Next steps include clustering detected anomalies into events and identifying their environmental drivers. We will continue to update our web application with advances in anomaly detection and monitoring. Our aim is to inform forecasting and early-warning systems as well as forest management strategies.