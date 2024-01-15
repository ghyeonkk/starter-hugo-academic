---
title: "Stacked Encoder–Decoder Transformer with Boundary Smoothing for Action Segmentation"
authors:
- admin
- Eunwoo Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-12-01T00:00:00Z"
doi: "https://doi.org/10.1049/ell2.12678"
draft: False

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Electronics Letters, vol. 58, no. 25, pp. 972‑974"
publication_short: ""

abstract: In this work, a new stacked encoder–decoder transformer (SEDT) model is proposed for action segmentation. SEDT is composed of a series of encoder–decoder modules, each of which consists of an encoder with self-attention layers and a decoder with cross-attention layers. By adding an encoder with self-attention before every decoder, it preserves local information along with global information. The proposed encoder–decoder pair also prevents the accumulation of errors that occur when features are propagated through decoders. Moreover, the approach performs boundary smoothing in order to handle ambiguous action boundaries. Experimental results for two popular benchmark datasets, “GTEA” and “50 Salads”, show that the proposed model is more effective in performance than existing temporal convolutional network based models and the attention-based model, ASFormer.

# Summary. An optional shortened abstract.
summary: 

tags:
- Video Understanding
- Action Segmentation
- Boundary Smoothing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/ell2.12678'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
