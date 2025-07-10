---
title: 'Serial Low-rank Adaptation of Vision Transformer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Houqiang Zhong
  - Shaocheng Shen
  - Ke Cai
  - Zhenglong Wu
  - Jiangchao Yao
  - Yuan Cheng
  - Xuefei Li
  - Xiaoyun Zhang
  - Li Song
  - Qiang Hu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2025-05-22T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Multimedia and Expo (ICME), 2025*
publication_short: In *IEEE International Conference on Multimedia and Expo (ICME), 2025*

abstract: 'Fine-tuning large pre-trained vision foundation models in a parameter-efficient manner is critical for downstream vision tasks, considering the practical constraints of computational and storage costs. Low-rank adaptation (LoRA) is a well-established technique in this domain, achieving impressive efficiency by reducing the parameter space to a low-rank form. However, developing more advanced low-rank adaptation methods to reduce parameters and memory requirements remains a significant challenge in resource-constrained application scenarios. In this study, we consider on top of the commonly used vision transformer and propose Serial LoRA, a novel LoRA variant that introduces a shared low-rank matrix serially composite with the attention mechanism. Such a design extracts the underlying commonality of parameters in adaptation, significantly reducing redundancy. Notably, Serial LoRA uses only 1/4 parameters of LoRA but achieves comparable performance in most cases. We conduct extensive experiments on a range of vision foundation models with the transformer structure, and the results confirm consistent superiority of our method.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2503.17750'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

