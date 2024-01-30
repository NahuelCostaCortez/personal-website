---
title: "ICFormer: A Deep Learning model for informed lithium-ion battery diagnosis and early knee detection"
authors:
- admin
- David Anseán
- Matthieu Dubarry
- Luciano Sánchez
author_notes:
date: "2023-12-01T00:00:00Z"
doi: "10.1016/j.jpowsour.2023.233910"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Power Sources*"
publication_short: ""

abstract: Accurate diagnosis of lithium-ion battery (LIB) degradation is critical for safe and reliable operation in real-world applications. In recent years, data-driven approaches powered by Machine Learning algorithms emerged as a promising solution, among which Deep Learning methods were proven to be effective for various tasks such as State of Charge and State of Health estimation and Remaining Useful Life prediction, however, their application for knee point estimation is still at an early stage. While experimental techniques, were demonstrated to be successful for detecting knees, current methods focus on tracking individual cycles rather than analyzing the overall trajectory of degradation, which could potentially offer better performance. In this paper, we introduce ICFormer, a novel Deep Learning model based on a Transformer encoder that leverages self-attention on the evolution of incremental capacity curves to accurately identify relevant changes in LIB degradation trajectories. The proposed model not only detects knees, but also anticipates them while also outperforming state-of-the-art approaches in diagnosing degradation modes. The effectiveness of the model is validated using both synthetic and experimental data. We demonstrate that the method can provide valuable knowledge on the factors contributing to capacity loss and offer advanced insights for battery management and predictive maintenance strategies.


# Summary. An optional shortened abstract.
summary: This work proposes a novel Deep Learning model based on a Transformer encoder to accurately estimate degradation modes and early detect knee points.

tags:
- Source Themes
featured: false

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S0378775323012867
url_code: https://github.com/NahuelCostaCortez/ICFormer
url_dataset: https://data.mendeley.com/datasets/bs2j56pn7y
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
projects: [Li-ion]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
