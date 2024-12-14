---
title: 'Few-shot generative compression approach for system health monitoring'

authors:
- admin
- Luciano Sánchez

author_notes:
  - ''

date: '2024-12-14T00:00:00Z'
doi: 'https://doi.org/10.1016/j.ress.2024.110749'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Reliability Engineering & System Safety*
publication_short: ""

abstract: Prognostics and Health Management (PHM) is essential for maintaining optimal performance in industrial environments. Data-driven methods, particularly those leveraging machine learning and deep learning, have demonstrated effectiveness in PHM-related tasks such as anomaly detection, fault diagnosis, and remaining useful life estimation (RUL). However, the scarcity of precise and labeled information often limits their applicability. In this paper, we introduce a novel approach tailored for cases where only monitoring data is available but very few instances are labeled. The proposed method relies on training a generative model in an unsupervised manner to construct a compressor, which is later used to compute a compressor-based distance metric derived from Kolmogorov complexity. When combined with minimal labeled data, the distance metric can be utilized to perform system health estimation. We demonstrate the effectiveness of the approach through two fleet diagnostic problems, where it surpasses the performance of both supervised and semi-supervised methods. Additionally, our method exhibits consistency in handling partial monitoring information, showcasing its robustness in real-world applications.


# Summary. An optional shortened abstract.
summary: This work proposes a compression-based approach for problems with limited labeled data.

tags:
- Source Themes
featured: false

links:
url_pdf: https://www.sciencedirect.com/science/article/pii/S0951832024008202
url_code: https://github.com/NahuelCostaCortez/rapidae/tree/nahuel
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
