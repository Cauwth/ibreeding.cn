---
title: G2P
summary: G2P works as an integrative environment offering comprehensive, unbiased evaluation analyses of the 16 GS models,which may be run in parallel on high-performance computing lusters. 
tags:
- Tools
date: "2023-08-04"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url:
- icon: link
  icon_pack: fas
  name: more
  url: https://g2p-env.github.io/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

authors: [""]

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

G2P works as an integrative environment offering comprehensive, unbiased evaluation analyses of the 16 GS models, which may be run in parallel on high-performance computing clusters. Based
on the evaluation outcome, G2P performs auto-ensemble algorithms that not only can automatically select the most precise models but also can integrate prediction results from multiple models. This functionality should further improve the precision of G2P prediction. Another noteworthy function is the
refinement design of the training set, in which G2P optimizes the training set based on the genetic diversity analysis of a studied population. Although the training samples in the optimized set are fewer than in the original set, the prediction precision is almost equivalent to that obtained when using the whole set. This functionality is quite useful in practice, as it reduces the cost of phenotyping when constructing training population. The G2P container and source codes are freely accessible at https://g2p-env.github.io/
---