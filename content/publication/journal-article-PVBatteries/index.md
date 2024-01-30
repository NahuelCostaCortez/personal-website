---
title: "Data-Driven Diagnosis of PV-Connected Batteries: Analysis of Two Years of Observed Irradiance"
authors:
- Matthieu Dubarry
- Fahim Yasir
- admin
- Dax Matthews
author_notes:
date: "2023-07-29T00:00:00Z"
doi: "10.3390/batteries9080395"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
journal: "*Batteries Journal*"
publication_short: ""

abstract: The diagnosis and prognosis of PV-connected batteries are complicated because cells might never experience controlled conditions during operation as both the charge and discharge duty cycles are sporadic. This work presents the application of a new methodology that enables diagnosis without the need for any maintenance cycle. It uses a 1-dimensional convolutional neural network trained on the output from a clear sky irradiance model and validated on the observed irradiances for 720 days of synthetic battery data generated from pyranometer irradiance observations. The analysis was performed from three angles, the impact of sky conditions, degradation composition, and degradation extent. Our results indicate that for days with over 50% clear sky or with an average irradiance over 650 W/m2, diagnosis with an average RMSE of 1.75% is obtainable independent of the composition of the degradation and of its extent.


# Summary. An optional shortened abstract.
summary: This work proposes a new methodology for opportunistic diagnosis using machine learning algorithms trained directly on photovoltaic battery charging data.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2313-0105/9/8/395
url_code: ''
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
projects: [Li-ion]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---