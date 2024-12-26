---
title: 'Physics-informed learning under epistemic uncertainty with an application to system health modeling'

authors:
- Luciano Sánchez
- admin
- José Otero
- Inés Couso

author_notes:
  - ''

date: '2023-10-01T00:00:00Z'
doi: '10.1016/j.ijar.2023.108988'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Approximate Reasoning*
publication_short: ""

abstract: This study proposes a methodology for developing deterioration models to estimate the remaining lifetime of a system using physics-informed learning. The approach consists of combining physical knowledge about the system with a set of data obtained from similar systems that have failed in the past to build a set of constraints on the evolution over time of the state of health of the system. The data consists of partial measurements of the system variables, taken from its commissioning to the present. The physical knowledge used comprises a set of differential equations that approximate the dynamics and aging of the system. In contrast to other studies, the physical model is not assumed to be accurate, but is considered to be an approximation of reality. Constraints on the temporal evolution of the state of health derived from this physical knowledge take into account its imprecision and consist of possibility distributions. In this study, the max-max, max-min and min-max regret principles are applied to extract the time evolution of the deterioration rate that best fits the constraints. The effectiveness of the proposed algorithm is evaluated by means of a comparative empirical analysis in different use cases, and the situations in which informed learning improves on purely data-driven algorithms are analyzed.


# Summary. An optional shortened abstract.
summary: This work proposes a methodology for developing deterioration models to estimate the remaining lifetime of a system using physics-informed learning (PIL).

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0951832023002351
url_code: 
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