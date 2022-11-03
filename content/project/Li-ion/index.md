---
title: Li-ion batteries
summary: Diagnosis and prognosis of lithium-ion batteries
tags:
  - Li-ion
date: '2021-12-01T00:00:00Z'

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

Since their commercialization in the early 1990s, lithium-ion batteries (LIBs) have been widely used in key commercial and industrial applications, ranging from portable electronics and transportation to storage systems. Unfortunately, the performance of LIBs decreases with operation due to parasitic reactions taking place at the positive and negative electrodes (PE and NE respectively), as well as in the electrolyte. In addition, some specific side reactions, such as lithium plating, can create safety risks. Both decreased performance and safety issues are a major concern for deployed LIB systems, especially when reliable and durable applications are critical. To assess LIB performance and ensure overall safety and reliability, it is necessary to determine the state of health (SOH). 

Recently, a new paradigm of non-invasive methodologies for assessing battery SOH has emerged thanks to recent improvements in processor capabilities and communications, and AI is expected to have a profound influence on future LIBs diagnostic and prognostic systems. However, the existing methodologies are still in their early stages and critical issues remain to be solved.

Degradation of LIBs is the result of a complex interaction between physical and chemical mechanisms within the battery, leading to loss of capacity and power. Degradation is path dependent and different uses such as temperatures, charging currents or cut-off voltages, can inhibit or exacerbate specific degradation mechanisms. These mechanisms are varied and can be grouped into degradation modes, which are loss of lithium inventory (LLI) and loss of active material (LAM) at the negative and positive electrodes (LAMNE and LAMPE respectively).

Although the degradation modes are widely known in the field, the underlying causes and effects in the battery are not always straightforward. As an example, LAM degradations are difficult to detect since they do not usually leave signals in the history of capacity loss but after a few cycles of regular operation, they manifest by causing the capacity to decay suddenly. Because of this, they are known in the literature as "silent" or "hidden" modes.

In addition to the increasing sophistication of the algorithms required, the amount of data needed for training is also critical, as battery data generation is challenging and time-consuming. The reality is that existing datasets, while providing valuable information, are sparse and only provide data from a few cells. This poses a major obstacle to the application of AI algorithms, as large amounts of data are generally required for the training process. In addition, models trained with these datasets can lead to a false sense of confidence in their performance, as the capacity loss decays linearly in most cases and tests are usually performed with a low variety of duty cycles that are quite often disconnected from real applications (e.g., constant current cycles). The actual data is much more sporadic and sub and supralinear degradations are more common.

Both future datasets and AI algorithms must take these limitations into account to realistically contribute to the diagnosis and prognosis of LIBs. Thus, their life cycles can be extended, and they can even be reused in other systems with less demanding requirements.
