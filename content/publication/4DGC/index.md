---
title: '4DGC: Rate-Aware 4D Gaussian Compression for Efficient Streamable Free-Viewpoint Video'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiang Hu
  - Zihan Zheng

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2025-05-24T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *CVPR Conference*
publication_short: In *CVPR*

abstract: '3D Gaussian Splatting (3DGS) has substantial potential for enabling photorealistic Free-Viewpoint Video (FVV) experiences. However, the vast number of Gaussians and their associated attributes poses significant challenges for storage and transmission. Existing methods typically handle dynamic 3DGS representation and compression separately, neglecting motion information and the rate-distortion (RD) trade-off during training, leading to performance degradation and increased model redundancy. To address this gap, we propose 4DGC, a novel rate-aware 4D Gaussian compression framework that significantly reduces storage size while maintaining superior RD performance for FVV. Specifically, 4DGC introduces a motion-aware dynamic Gaussian representation that utilizes a compact motion grid combined with sparse compensated Gaussians to exploit inter-frame similarities. This representation effectively handles large motions, preserving quality and reducing temporal redundancy. Furthermore, we present an end-to-end compression scheme that employs differentiable quantization and a tiny implicit entropy model to compress the motion grid and compensated Gaussians efficiently. The entire framework is jointly optimized using a rate-distortion trade-off. Extensive experiments demonstrate that 4DGC supports variable bitrates and consistently outperforms existing methods in RD performance across multiple datasets.'

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
url_code: 'https://github.com/qianghu-huber/4DGC'
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/qianghu-huber/4DGC'
url_slides: ''
url_source: 'https://arxiv.org/pdf/2503.18421'
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

