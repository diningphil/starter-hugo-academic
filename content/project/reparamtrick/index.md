---
title: Notes on the Reparametrization Trick
summary:
tags:
  - Variational Auto-Encoders
date: "2018-12-05T00:00:00Z"

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

One of the most popular articles of the last years in the Machine Learning community is the [Auto-Encoding Variational Bayes](https://arxiv.org/pdf/1312.6114.pdf), which also includes the so-called reparametrization trick. Intrigued by what was sketched in the article, I decided to work out the details of this reparametrization, covering 2 of the 3 cases described (but I guess the third one can be derived from the first 2). I want to share my calculations with you. I have learned (and reviewed) a lot in the process, which was not directly related to the equations themselves. Sharing is the only way to make real progress as a community. Have a look {{< staticref "uploads/reparamtrick_notes.pdf" "newtab" >}}Here{{< /staticref >}}, and please contact me in case the steps are not correct or contain imprecise notation.

*Update, 2018-12-10*: I have added the solution of the integrals of Appendix B. This was really useful to get familiar with the gaussian integral and Fubini's theorem.

Special thanks to Iacopo Ripoli for his decisive and helpful insights!
