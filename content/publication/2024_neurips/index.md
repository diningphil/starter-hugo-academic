---
title: "Higher-Rank Irreducible Cartesian Tensors for Equivariant Message Passing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Viktor Zaverkin
- Francesco Alesiani
- Takashi Maruyama
- admin
- Henrik Christiansen
- Makoto Takamoto
- Nicolas Weber
- Mathias Niepert

# Author notes (optional)
author_notes:

date: "2024-09-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Advances in Neural Information Processing Systems
publication_short: NeurIPS 2024

abstract:

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2405.14253'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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
In this paper I try to address the following question: "Is it really worth to build a k-Nearest Neighbor graph from tabular data and then apply deep graph nets on top of it to classify each sample in the table?" This is something people tend to do, and I have always been skeptical about it. Now we have a very good indication, which I also tried to justify theoretically, that a k-NN graph is not the best structure to use if we want to gain some real advantages (under some mild conditions). I also argue that new methods of building synthetic graphs are necessary if we want to exploit some "latent" structure between the samples of a dataset.
