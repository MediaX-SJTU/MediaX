---
title: 'TD-BFR: Truncated Diffusion Model for Efficient Blind Face Restoration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ziying Zhang
  - Xiang Gao
  - Zhixin Wang
  - Qiang Hu
  - Xiaoyun Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2025-05-26T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Multimedia and Expo (ICME), 2025*
publication_short: In *IEEE International Conference on Multimedia and Expo (ICME), 2025*

abstract: 'Diffusion-based methodologies have shown significant potential in blind face restoration (BFR), leveraging their robust generative capabilities. However, they are often criticized for two significant problems: 1) slow training and inference speed, and 2) inadequate recovery of fine-grained facial details. To address these problems, we propose a novel Truncated Diffusion model for efficient Blind Face Restoration (TD-BFR), a three-stage paradigm tailored for the progressive resolution of degraded images. Specifically, TD-BFR utilizes an innovative truncated sampling method, starting from low-quality (LQ) images at low resolution to enhance sampling speed, and then introduces an adaptive degradation removal module to handle unknown degradations and connect the generation processes across different resolutions. Additionally, we further adapt the priors of pre-trained diffusion models to recover rich facial details. Our method efficiently restores high-quality images in a coarse-to-fine manner and experimental results demonstrate that TD-BFR is, on average, faster than current state-of-the-art diffusion-based BFR methods while maintaining competitive quality.'

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
url_source: 'https://arxiv.org/abs/2503.20537'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

