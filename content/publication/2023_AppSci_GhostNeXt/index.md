---
title: "GhostNeXt: Rethinking Module Configurations for Efficient Model Design"
authors:
- Kiseong Hong
- admin
- Eunwoo Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-03-01T00:00:00Z"
doi: "https://doi.org/10.3390/app13053301"
draft: False

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Applied Sciences, vol. 13, no. 5"
publication_short: "Applied Sciences"

abstract: Despite the continuous development of convolutional neural networks, it remains a challenge to achieve performance improvement with fewer parameters and floating point operations (FLOPs) as a light-weight model. In particular, excessive expressive power on a module is a crucial cause of skyrocketing the computational cost of the entire network. We argue that it is necessary to optimize the entire network by optimizing single modules or blocks of the network. Therefore, we propose GhostNeXt, a promising alternative to GhostNet, by adjusting the module configuration inside the Ghost block. We introduce a controller to select channel operations of the module dynamically. It holds a plug-and-play component that is more useful than the existing approach. Experiments on several classification tasks demonstrate that the proposed method is a better alternative to convolution layers in baseline models. GhostNeXt achieves competitive recognition performance compared to GhostNet and other popular models while reducing computational costs on the benchmark datasets.

# Summary. An optional shortened abstract.
summary: 

tags: 
- Module Configuration
- Resource-Efficient Network
- Network Design
featured: false

# links:
# - name: ""
#  url: ""
url_pdf: ''
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
