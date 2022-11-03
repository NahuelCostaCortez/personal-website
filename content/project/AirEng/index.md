---
title: Aircraft Engines
summary: Remaining useful life of aircraft engines
tags:
  - Aircraft
date: '2020-12-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo generated with Stable Difussion
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

The advancement of technology has resulted in significant improvements in the safety and maintenance of aircraft engines. Prognostic technologies have been essential in this process since aircrafts are subjected to different conditions throughout their life cycle that cause degradation and ultimately lead to failure. Thus, being able to provide safe monitoring in these systems translates to a notable increase in reliability and also an extension in their useful life, which in the end also means remarkable savings for manufacturing companies.

In order to monitor performance and prevent operation under undesirable conditions, the engines have several built-in sensors from which data is routinely collected. Over the years, the amount of information collected has increased and this has paved the way for more complex analysis in favor of life-extending maintenance. However, traditional strategies such as scheduled preventive maintenance or corrective maintenance are increasingly unable to meet the growing industrial demand in terms of efficiency and reliability. In recent years, metrics such as Remaining Useful Life (RUL) have gained popularity and have been established as key elements to improve maintenance and avoid engineering, safety and reliability failures. Consequently, this would make it possible to determine engine deterioration, increase flight time and reduce maintenance costs.

Traditionally. anomaly detection is widely adopted in the field, but not so much the study of the phenomena that cause the breakpoint between normal and abnormal operation. However, in RUL estimation the aim for a complete and interpretable diagnosis should be to model the evolution of the system over time to know at what speed it evolves towards anomalous situations. This means, not to pursue the identification of anomalies, but rather to find when the engine start deteriorating at a different rate than it did before.

The presence of anomalies is indeed correlated with RUL as they usually correspond to low RUL values. However, two systems can be in the same initial state but have a different evolution over time, so successive system states cannot be studied independently as is done in anomaly detection. Instead, RUL estimation must be linked to the temporal analysis of complete historical periods.

In addition, monitoring data is subject to limitations. Although the number of sensors is tending to increase, the number of recorded events is still limited and not all sensors are of equal diagnostic importance. Also, many of the records are incomplete, have spurious values or are sensitive to natural factors such as wind, the number of passengers or trajectory changes and can cause noticeable peaks in each signal, which ultimately corrupts the data.

An end-to-end model capable of dealing with the above-mentioned problems should greatly reduce the likelihood of an aircraft experiencing an unforeseen event, which represents an invaluable economic saving for manufacturing companies.