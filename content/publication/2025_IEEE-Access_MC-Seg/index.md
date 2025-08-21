---
title: "Mitigating Class Confusion in Class-Incremental Semantic Segmentation"
authors:
- Nayoung Ko
- admin
- Eunwoo Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-05-12T00:00:00Z"
doi: "https://doi.org/10.1109/ICTC62082.2024.10827159"
draft: False

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: Class-incremental semantic segmentation (CSS) aims to continuously classify every pixel in an image to its corresponding semantic class. Existing CSS models suffer from two challenges"\\:" catastrophic forgetting and background shift. Moreover, when new classes are introduced over time, they struggle to differentiate between new and old classes that are visually similar. We refer to this problem as class confusion. To address the above issues, we propose a novel CSS approach to mitigate class confusion, called MC-Seg. First, we introduce a graph attention decoder (GAD) to capture semantic relationships between embeddings, enabling clearer segmentation across classes. GAD uses joint embeddings as nodes in a graph, enabling visual embeddings to incorporate class information. Furthermore, we propose similarity-aware class discrimination (SCD) to prevent old knowledge from being overwritten by new knowledge, particularly when the two are visually similar. Since visually similar classes are more likely to be confused with each other, SCD increases the distances between their embeddings to preserve essential distinctions. Moreover, to retain the knowledge of other, non-similar classes, we maintain the distances between their embeddings. Extensive experiments on PASCAL VOC 2012, ADE20K and PASCAL Context show that MC-Seg outperforms state-of-the-art CSS methods, especially in alleviating class confusion in incremental learning.
# Summary. An optional shortened abstract.
summary: 

tags: 
- Class-incremental Semantic Segmentation
- Class Confusion
- Graph Attention
- Similarity-aware Class Discrimination
featured: false

# links:
# - name: ""
#  url: ""
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11002496'
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
