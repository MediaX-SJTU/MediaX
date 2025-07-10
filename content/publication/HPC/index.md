---
title: 'HPC: Hierarchical Progressive Coding Framework for Volumetric Video'

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

date: "2024-08-28T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the ACM International Conference on Multimedia(MM), 2024
publication_short: Proceedings of the ACM International Conference on Multimedia(MM), 2024

abstract: 'Volumetric video based on Neural Radiance Field (NeRF) holds vast potential for various 3D applications, but its substantial data volume poses significant challenges for compression and transmission. Current NeRF compression lacks the flexibility to adjust video quality and bitrate within a single model for various network and device capacities. To address these issues, we propose HPC, a novel hierarchical progressive volumetric video coding framework achieving variable bitrate using a single model. Specifically, HPC introduces a hierarchical representation with a multi-resolution residual radiance field to reduce temporal redundancy in long-duration sequences while simultaneously generating various levels of detail. Then, we propose an end-to-end progressive learning approach with a multi-rate-distortion loss function to jointly optimize both hierarchical representation and compression. Our HPC trained only once can realize multiple compression levels, while the current methods need to train multiple fixed-bitrate models for different rate-distortion (RD) tradeoffs. Extensive experiments demonstrate that HPC achieves flexible quality levels with variable bitrate by a single model and exhibits competitive RD performance, even outperforming fixed-bitrate models across various datasets.'

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
url_source: 'https://dl.acm.org/doi/abs/10.1145/3664647.3681107'
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
