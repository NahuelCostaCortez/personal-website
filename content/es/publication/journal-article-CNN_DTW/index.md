---
title: 'Li-ion battery degradation modes diagnosis via Convolutional Neural Networks'

authors:
- admin
- Luciano Sánchez
- David Anseán
- Matthieu Dubarry

author_notes:
  - ''
  
date: '2022-09-01T00:00:00Z'
doi: '10.1016/j.est.2022.105558'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Energy Storage*
publication_short: ""

abstract: Lithium-ion batteries are ubiquitous in modern society with a presence in storage systems, electric cars, portable electronics, and many more applications. Consequently, to enable safe and reliable use of LIB systems, diagnosis and prognosis have become critical. Within the field of Artificial Intelligence, Deep Learning algorithms have achieved significant impacts for image or object recognition, yet their application for battery diagnosis is still at an early developing stage. In this paper, we propose a novel approach for battery degradation diagnosis based on the representation of battery data as images, in order to leverage the use of well-established Convolutional Neural Networks. Accuracy for diagnosis, via the quantification of degradation modes was tested on synthetic data. Our approach was shown to be more accurate than current methodologies with Root Mean Squared Errors around 2% on average for 1000 duty cycles compared to between 2.64 to 7.27% for other state-of-the-art algorithms. We also show that the proposed methodology adapts to various cell chemistries and constructive configurations, and validate its applicability to a real-world scenario with experimental data from commercial LIBs.


# Summary. An optional shortened abstract.
summary: This work proposes a new representation of battery data as images, in order to leverage the use of well-established Convolutional Neural Networks for battery degradation diagnosis.

tags:
- Source Themes
featured: false

links:
- name: Demo
  url: https://huggingface.co/spaces/NahuelCosta/DTW-CNN
url_pdf: https://www.sciencedirect.com/science/article/pii/S2352152X22015493
url_code: https://github.com/NahuelCostaCortez/DTW-Li-ion-Diagnosis
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
projects: [PHM]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
