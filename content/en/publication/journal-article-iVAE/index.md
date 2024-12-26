---
title: 'Integrating imprecise data in generative models using interval-valued Variational Autoencoders'

authors:
- Luciano Sánchez
- admin
- Inés Couso
- Olivier Strauss


author_notes:
  - ''

date: '2025-02-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.inffus.2024.102659'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Information Fusion*
publication_short: ""

abstract: Variational Autoencoders (VAEs) enable the integration of diverse data sources into a unified latent representation, facilitating the fusion of information from various inputs and the creation of disentangled representations that separate different factors of variation in the data. Traditional VAEs, however, are limited by assuming a single prior distribution for latent variables, which restricts their ability to handle epistemic uncertainty from imprecise measurements and incomplete data. This paper introduces the Interval-Valued Variational Autoencoder (iVAE), which employs a family of prior distributions and incorporates specialized neurons and redefined objective functions for handling interval-valued data. This architecture maintains computational efficiency while extending the model’s applicability to scenarios with pronounced epistemic uncertainty. The iVAE’s efficacy is demonstrated in managing two types of data - intrinsically interval-valued and noisy data preprocessed into interval formats. The first category is exemplified by a graphical analysis of questionnaires, while the second involves case studies focused on estimating the remaining useful life of aviation engines, where the iVAE outperforms traditional methods, thereby providing more accurate diagnostics and robust predictions.


# Summary. An optional shortened abstract.
summary: VAE for interval-values data.

tags:
- Source Themes
featured: false

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S1566253524004378
url_code: https://github.com/NahuelCostaCortez/rapidae
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
projects: [PHM]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
