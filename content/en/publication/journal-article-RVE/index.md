---
title: "Variational encoding approach for interpretable assessment of remaining useful life estimation"

authors:
- admin
- Luciano Sánchez

author_notes:
  - ''
  
date: "2022-06-01T00:00:00Z"
doi: "10.1016/j.ress.2022.108353"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Reliability Engineering & System Safety*
publication_short: ""

abstract: A new method for evaluating aircraft engine monitoring data is proposed. Commonly, prognostics and health management systems use knowledge of the degradation processes of certain engine components together with professional expert opinion to predict the Remaining Useful Life (RUL). New data-driven approaches have emerged to provide accurate diagnostics without relying on such costly processes. However, most of them lack an explanatory component to understand model learning and/or the nature of the data. To overcome this gap we propose a novel approach based on variational encoding. The model consists of a recurrent encoder and a regression model, the encoder learns to compress the input data to a latent space that serves as a basis to build a self-explanatory map that can visually evaluate the rate of deterioration of aircraft engines. Obtaining such a latent space is regularized by a new cost function guided by variational inference and a term that penalizes prediction errors. Consequently, not only an interpretable assessment is achieved but also a remarkable prognostic accuracy, outperforming most of the state-of-the-art approaches on the popular simulation dataset C-MAPSS from NASA. In addition, we demonstrate the application of our method in a real-world scenario with data from actual Turbofan engines.


# Summary. An optional shortened abstract.
summary: This work proposes a novel approach based on variational encoding to evaluate aircraft engine monitoring data.

tags:
- Source Themes
featured: false

links:
- name: Demo
  url: https://huggingface.co/spaces/NahuelCosta/RUL-Variational
url_pdf: https://www.sciencedirect.com/science/article/pii/S0951832022000321
url_code: https://github.com/NahuelCostaCortez/Remaining-Useful-Life-Estimation-Variational
url_dataset: https://www.kaggle.com/datasets/behrad3d/nasa-cmaps
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