---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SourceSet"
summary: "A Graphical Model Approach to Identify Primary Genes in Perturbed Biological Pathways"
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
  url: https://cran.rstudio.com/web/packages/SourceSet/index.html
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

SourceSet is a statisticla method to distinguish between the primary and the secondary dysregulation within a Gaussian graphical model context. It compares gene expression profiles in the control and in the perturbed condition and detects the differences in both the mean and the covariance parameters with a series of likelihood ratio tests. The resulting evidence is used to infer the primary and the secondary set, i.e. the genes responsible for the primary dysregulation, and the genes affected by the perturbation through network propagation. 

SourceSet demonstrates high specificity and sensitivity in different simulated scenarios and on several real biological case studies. In order to fit into the more traditional pathway analysis framework, SourceSet R package also extends the analysis from a single to multiple pathways and provides several graphical outputs, including Cytoscape visualization to browse the results.

Salviato E, Djordjilović V, Chiogna M, Romualdi C (2019) SourceSet: A graphical model approach to identify primary genes in perturbed biological pathways. PLOS Computational Biology 15(10): e1007357. https://doi.org/10.1371/journal.pcbi.1007357