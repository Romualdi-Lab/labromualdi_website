---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SimPATHy"
summary: "a new method for simulating data from perturbed biological PATHways"
authors: []
tags: [rpackage]
categories: [r]
date: 2019-10-09T08:00:20-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: rpackage
  url: https://cran.r-project.org/web/packages/simPATHy/index.html
  icon_pack: fab
  icon: 

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

simPATHy is a model for simulating data from perturbed biological pathways. It is implemented as an  R package and produces synthetic datasets useful to validate GSA methods focused on topological properties of biological networks. 

Given a graph structure representing a biological network, functions in simPATHy allow simulating data in two different conditions. The two conditions, assumed to share the same graphical structure, are referred to as reference and dysregulated condition. Dysregulation is defined as a change in the strength of the links between network nodes. Such changes can be interpreted as activation/deactivation of network connections.

Elisa Salviato, Vera Djordjilović, Monica Chiogna, Chiara Romualdi, simPATHy: a new method for simulating data from perturbed biological PATHways, Bioinformatics, Volume 33, Issue 3, 1 February 2017, Pages 456–457, https://doi.org/10.1093/bioinformatics/btw642