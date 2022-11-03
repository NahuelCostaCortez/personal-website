---
title: Cardiovascular Diseases
summary: Diagnosis and treatment of Atrial Fibrillation
tags:
  - FA
date: '2018-12-01T00:00:00Z'

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

Heart diseases are among the leading causes of death worldwide. Atrial Fibrillation (AF) is the most common cardiovascular disorder, and its treatment involves the use of pacemakers to regulate the heart rhythm. Unfortunately, there is currently no standard procedure for diagnosing the disease state beyond the check of the data captured by medical specialists.

The disease usually evolves from paroxysmal arrhythmias (arrhythmias that come and go spontaneously) to persistent arrhythmias (episodes that last more than 7 days and do not end without external intervention) or to permanent arrhythmias (uninterrupted episodes). It is caused by a problem in the electrical system of the heart that leads to an irregular heartbeat in which the upper chambers of the heart, the atria, fibrillate. Because of the loss of synchrony in the heart rhythm, symptoms such as chest pains or dizziness may appear, and in the worst scenarios, it can cause the formation of clots inside the heart which, if they reach the bloodstream, can result in serious problems such as stroke.

The records stored by pacemakers are generally limited, as a long history would mean the individual is already in the final stage of the disease. This limitation makes it difficult to obtain a model that fits the characteristics of the data and understand the patient's condition. Furthermore, the disease evolves over time, making the data non-stationary and it is precisely the changes in the properties of the data that determine the progression from paroxysmal to permanent arrhythmias.

There are even more difficulties, the algorithm used by pacemakers to determine the duration of arrhythmia episodes is not completely reliable. The device parameters are adjusted prioritizing safety, so the false positive rate is high. This results in long AF episodes that are sometimes erroneously reported as sets of short episodes, so preprocessing is needed to account for these spurious events, which in turn causes the number of available episodes to be further reduced.

Given these facts, the progression of AF is a complex process that depends on many different factors. Ideally, the aim is to find a model that would be able to learn, from a few dozen recordings, the specific properties of the disease and at the same time can extrapolate the breaking point between paroxysmal and permanent AF. In this way, it would be possible to provide, from intracardiac data, a diagnosis of the patient's situation that would make it possible to show how the disease will progress in the near future. This would enable medical specialists to prevent any future complications, and thus improve the health and quality of life of the patient.