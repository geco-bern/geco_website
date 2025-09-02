---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Master thesis - Detecting water stress via land surface temperatures"
event:
event_url:
location: Institute of Geography, University of Bern
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2025-08-14T08:36:01+01:00
date_end: 2025-08-14T08:36:01+01:00
all_day: true

# Schedule page publish date (NOT event date).
publishDate: 2025-08-14T08:36:01+01:00

authors: [Benjamin Stocker]
tags: [remote sensing, LST, water stress, MSc]

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Image source: https://ecostress.jpl.nasa.gov/"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


**Context:** Land surface temperatures (LST) can be sensed from space. They reflect climatic conditions at the land surface (air temperature, radiation), and surface properties. The clue is that they also reflect to what extent water vapour fluxes cool surfaces and that plants have a strong influence on them. Hence, the activity of plants and the degree to which they are water limited have an imprit on remotely sensed LST. The challenge is to disentangle this signal from (big) satellite data. If a solution is found, it will yield a novel approach for interpreting high resolution LST data for informing our understanding of vegetation water stress across space.

**Aim:** Developing a quantitative method for measuring the degree of vegetation water limitation effects on LST, thereby deriving a spatial picture of water limitation across the landscape during droughts.

**Methods:** This project will develop a machine learning-based method that estimates a potential ("moist") LST, using [ECOSTRESS](https://ecostress.jpl.nasa.gov/) LST data, paired with climate variables and a set of time-invariant layers that characterise land surface properties. Comparison of "moist" vs. actual LST should yield quantitative insight into the degree of water limitation.


**Requirements:**

- Introductory course on statistical or machine learning-based modelling.
- Experience working with R or other data science tools is a prerequisite.
- The student writes the thesis in English.

**Supervision:** Prof. Benjamin Stocker
