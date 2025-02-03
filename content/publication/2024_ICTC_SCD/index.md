---
title: "Similarity-Aware Class Discrimination in Class-Incremental Semantic Segmentation"
authors:
- admin
- Nayoung Ko
- Eunwoo Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-10-01T00:00:00Z"
doi: "https://doi.org/10.1109/ICTC62082.2024.10827159"
draft: False

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: " 2024 15th International Conference on Information and Communication Technology Convergence (ICTC)"
publication_short: ""

abstract: Class-incremental semantic segmentation faces challenges in retaining the knowledge of old classes while learning new ones. Catastrophic forgetting and background shift are the primary hurdles causing performance degradation. Moreover, class confusion arises when new classes share categorical similarities with existing ones. Due to class confusion, the class-incremental semantic segmentation model overwrites the knowledge of old classes with similar new classes. In this paper, we introduce Similarity-aware Class Discrimination (SCD) to address the class confusion problem. SCD increases the distance between classes that share categorical similarities (i.e., visually similar but different classes) in the embedding space, preventing new knowledge from overwriting old knowledge. This approach encourages the model to discriminate between similar categorical classes, mitigating class confusion in class-incremental semantic segmentation. Our method surpasses existing CNN-based and transformer-based class-incremental semantic segmentation methods in PASCAL VOC 2012.
# Summary. An optional shortened abstract.
summary: 

tags: 
- Class-incremental Semantic Segmentation
- Class Confusion
- Similarity-aware Class Discrimination
featured: false

# links:
# - name: ""
#  url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10827159'
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  caption:
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
