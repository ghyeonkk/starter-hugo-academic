---
title: "GhostNeXt: Rethinking Module Configurations for Efficient Model Design"
authors:
- Hyundong Jin
- admin
- Chanho Ahn
- Eunwoo Kim
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-07-14T00:00:00Z"
doi: ""
draft: False

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)"
publication_short: ""

abstract: Deep neural networks suffer from catastrophic forgetting in continual learning, where they tend to lose information about previously learned tasks when optimizing a new incoming task. Recent strategies isolate the important parameters for previous tasks to retain old knowledge while learning the new task. However, using the fixed old knowledge might act as an obstacle to capturing novel representations. To overcome this limitation, we propose a framework that evolves the previously allocated parameters by absorbing the knowledge of the new task. The approach performs under two different networks. The base network learns knowledge of sequential tasks, and the sparsity-inducing hypernetwork generates parameters for each time step for evolving old knowledge. The generated parameters transform old parameters of the base network to reflect the new knowledge. We design the hypernetwork to generate sparse parameters conditional to the task-specific information and the structural information of the base network. We evaluate the proposed approach on class-incremental and taskincremental learning scenarios for image classification and video action recognition tasks. Experimental results show that the proposed method consistently outperforms a large variety of continual learning approaches for those scenarios by evolving old knowledge.
# Summary. An optional shortened abstract.
summary: 

tags: 
- 
- 
- 
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
