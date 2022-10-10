---
title: Supervised Clustering for Fact-Checked Claim Retrieval
summary: 'Addressed the task of verified claim retrieval - linking an unseen claim to previously-seen claims which have already been fact-checked. Used supervised clustering approach which defined a similarity measure between
claims and facts using BERT-based representations in order to form a k-nearest neighbor graph. Clusters are then constructed by partitioning this graph such that no cluster contains more than one fact.'
tags:
  - Deep Learning
date: '2021-12-15T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/dhdhagar/claim2fact'

image:
  caption: Stock Photo from Pexels
  focal_point: Smart

#links:
# - icon: twitter
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
# slides: example
---