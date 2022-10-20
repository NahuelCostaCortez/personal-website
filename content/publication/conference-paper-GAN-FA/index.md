---
title: 'Graphical analysis of the progression of atrial arrhythmia through an ensemble of Generative Adversarial Network Discriminators'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jesús Fernández
  - Inés Couso
  - Luciano Sánchez


# Author notes (optional)
author_notes:
  - ''

date: '2020-09-01T00:00:00Z'
doi: '10.2991/eusflat-19.2019.78'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Conference of the European Society for Fuzzy Logic and Technology*
publication_short: In *EUSFLAT*

abstract: Logs of arrhythmia episodes in patients with pacemakers are used to estimate the temporal progression of atrial arrhythmia. In order to attain an early detection, a stream of dates and episode lengths are fed to an array of detectors, each of which is responsive to a narrow range of arrhythmias. The outputs of these detectors are organized on a projection map, used by the specialist to assess the risk in the evolution of the patient. Each of the mentioned detectors is a recurrent LSTM network, that is in turn the discriminating element of a GAN that has been trained to generate temporal sequences of values of the degrees of truth that the arrhythmia episodes are not isolated.

# Summary. An optional shortened abstract.
summary: This work presents a graphical analysis of the progression of atrial arrhythmia through an ensemble of Generative Adversarial Network Discriminators.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://www.atlantis-press.com/proceedings/eusflat-19/125914848
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
