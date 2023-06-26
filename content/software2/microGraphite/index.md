---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "microGraphite"
summary: "An R  pipeline to perform topological pathway analysis integrating gene and miRNA expression profiles"
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

miRNAs have been extensively studied and hundreds of target genes have been found. However, despite all these efforts, signaling pathways that are the formal description of biological circuits, contain very few miRNAs. This penalizes pathway analyses, widely used and essential approaches to enhance transcriptome measurements interpretations.

To overcome this limitation we developed micrographite, an R pipeline able to integrate pathway information with predicted and validated miRNA–target interactions and to perform integrated topological analyses of miRNA and gene expression profiles to identify miRNA–gene circuits.

Calura E, Martini P, Sales G, Beltrame L, Chiorino G, D'Incalci M, Marchini S, Romualdi C. Wiring miRNAs to pathways: a topological approach to integrate miRNA and mRNA expression profiles. Nucleic Acids Res. 2014 Jun;42(11):e96. doi: 10.1093/nar/gku354.