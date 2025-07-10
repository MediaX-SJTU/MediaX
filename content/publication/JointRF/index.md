---
title: 'JointRF: End-to-End Joint Optimization for Dynamic Neural Radiance Field Representation and Compression Video'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zihan Zheng
  - Houqiang Zhong
  - Qiang Hu
  - Xiaoyun Zhang
  - Li Song
  - Ya Zhang
  - Yanfeng Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2024-06-08T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing (ICIP), 2024*
publication_short: In *IEEE International Conference on Image Processing (ICIP), 2024*

abstract: 'Neural Radiance Field (NeRF) excels in photo-realistically static scenes, inspiring numerous efforts to facilitate volumetric videos. However, rendering dynamic and long-sequence radiance fields remains challenging due to the significant data required to represent volumetric videos. In this paper, we propose a novel end-to-end joint optimization scheme of dynamic NeRF representation and compression, called JointRF, thus achieving significantly improved quality and compression efficiency against the previous methods. Specifically, JointRF employs a compact residual feature grid and a coefficient feature grid to represent the dynamic NeRF. This representation handles large motions without compromising quality while concurrently diminishing temporal redundancy. We also introduce a sequential feature compression subnetwork to further reduce spatial-temporal redundancy. Finally, the representation and compression subnetworks are end-to-end trained combined within the JointRF. Extensive experiments demonstrate that JointRF can achieve superior compression performance across various datasets.'

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
url_source: 'https://arxiv.org/abs/2405.14452'
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

