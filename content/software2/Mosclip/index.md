---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MOSCLIP"
summary: "R package for multi-omic topological pathway analysis looking for survival-associated gene modules"
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
- name: rpackages
  url: 
  icon_pack: fab
  icon: github

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

MOSClip ((Multi-Omics Survival Clip) is a multi-omic statistical approach based on pathway topology. It exploits the topology of pathway annotations and integrates multi-omics data to identify pathways or pathway modules associated with right-censored survival data.

MOSClip is implemented as an R package. It is highly flexible, accepting from one to many omics datasets, also allowing the use and combination of different data reduction strategies. It furthermore contains several tools to graphically summarize the results and help the user during data interpretation. These features make MOSClip a useful and versatile tool for omics integration analyses.

Martini P, Chiogna M, Calura E, Romualdi C. MOSClip: multi-omic and survival
pathway analysis for the identification of survival associated gene and modules.
Nucleic Acids Res. 2019 Aug 22;47(14):e80. doi: 10.1093/nar/gkz324.