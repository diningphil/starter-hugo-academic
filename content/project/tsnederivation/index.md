---
title: Derivations of SNE and t-SNE
summary:
tags:
- Dimensionality Reduction
date: "2018-11-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image taken from original paper
  focal_point: Smart

links:
# icon: twitter
#  icon_pack: fab
#  name: Follow
#  url:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Recently I was looking at Stochastic Neigbhor Embedding [(SNE)](https://papers.nips.cc/paper/2276-stochastic-neighbor-embedding.pdf) and its t-distributed version [(t-SNE)](http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf), but I could not find the exact steps to derive the gradient of the loss function (there are small errors in the t-SNE article and no info in the SNE one), so I decided to carry on the derivation and share it. I hope this can be of any help to those who are studying the same topic. {{< staticref "uploads/sne_tsne.pdf" "newtab" >}}Here{{< /staticref >}} you find the pdf: please let me know if you spot an error! (Picture taken from t-SNE paper)
