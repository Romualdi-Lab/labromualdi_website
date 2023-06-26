---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PsiNorm"
summary: "a scalable normalization for single-cell RNA-seq data"
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
- name: R
  url: https://bioconductor.org/packages/scone/
  icon_pack: fab
  icon: R

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

PsiNorm, a between-sample normalization method based on the power-law Pareto distribution parameter estimate. We show that Pareto distribution well resembles scRNA-seq data, especially those coming from platforms that employ unique molecular identifiers (UMIs). 

Motivated by this result, we implement PsiNorm, a simple and highly scalable normalization method. We benchmark PsiNorm against seven other methods in terms of cluster identification, concordance and computational resources required. We demonstrate that PsiNorm is among the top performing methods showing a good trade-off between accuracy and scalability.

Borella M, Martello G, Risso D, Romualdi C. PsiNorm: a scalable normalization for single-cell RNA-seq data. Bioinformatics. 2021 Sep 9;38(1):164–72. doi: 10.1093/bioinformatics/btab641.