---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "gINTomics"
summary: "An R package for Multi-Omics data integration and visualization"
authors: ["Angelo Velle"]
tags: [rpackage, shinyapp]
categories: [r]
date: 2023-07-21T08:00:20-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Right"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: rpackage
  url: https://www.bioconductor.org/packages/release/bioc/html/gINTomics.html
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


gINTomics is an R package for Multi-Omics data integration and visualization. gINTomics is designed to detect the association between the expression of a target and of its regulators, taking into account also their genomics modifications such as Copy Number Variations (CNV) and methylation. For RNA sequencing data, the counts will be fitted using a negative binomial model, while in the case of microarray or other types of data, a linear model will be applied. In some cases the number of regulators for a given target could be very high, in order to handle this eventuality, we provide a penalized linear model that will automatically keep only the most important regulators. All the models are gene-specific, so each gene/miRNA will have its own model with its covariates. The package will automatically download information about TF-target couples (dorothea), miRNA-target couples (multiMiR) and TF-miRNA couples (TransmiR). The couples will be used to define the covariates used in the integration models.

