---
title: "Semi-Supervised Recurrent Variational Autoencoder Approach for Visual Diagnosis of Atrial Fibrillation"
authors:
- admin
- Luciano Sánchez
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-03-09T00:00:00Z"
doi: "10.1109/ACCESS.2021.3064854"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: ""

abstract: In this work we propose a semi-supervised framework to visually assess the progression of time series. To this end, we present a recurrent version of the VAE to exploit the generative properties that lead it to learn in an unsupervised way a continuous compressed representation of the data. We introduce a classifier in the VAE training process to control the regulation of the latent space, allowing the network to learn latent variables that set the basis for creating an explainable evaluation of the data. We use the proposed framework to address the diagnosis of Atrial Fibrillation (AF) first validating it with simulated data with known properties and subsequently testing it with intracardiac data obtained from pacemakers and defibrillator systems.


# Summary. An optional shortened abstract.
summary: This work proposes a semi-supervised framework to visually assess the progression of time series.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9373315
url_code: https://github.com/NahuelCostaCortez/RVAE
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [FA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---