---
title: 'MegaFusion: Extend Diffusion Models towards Higher-resolution Image Generation without Further Tuning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haoning Wu
  - Shaocheng Shen
  - Qiang Hu
  - Xiaoyun Zhang
  - Ya Zhang
  - Yanfeng Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2024-08-18T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Winter Conference on Applications of Computer Vision (WACV), 2025.
publication_short: Winter Conference on Applications of Computer Vision (WACV), 2025.

abstract: Diffusion models have emerged as frontrunners in text-to-image generation, but their fixed image resolution during training often leads to challenges in high-resolution image generation, such as semantic deviations and object replication. This paper introduces MegaFusion, a novel approach that extends existing diffusion-based text-to-image models towards efficient higher-resolution generation without additional fine-tuning or adaptation. Specifically, we employ an innovative truncate and relay strategy to bridge the denoising processes across different resolutions, allowing for high-resolution image generation in a coarse-to-fine manner. Moreover, by integrating dilated convolutions and noise re-scheduling, we further adapt the model's priors for higher resolution. The versatility and efficacy of MegaFusion make it universally applicable to both latent-space and pixel-space diffusion models, along with other derivative models. Extensive experiments confirm that MegaFusion significantly boosts the capability of existing models to pro-duce images of megapixels and various aspect ratios, while only requiring about 40% of the original computational cost.

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
url_code: 'https://github.com/haoningwu3639/MegaFusion'
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/haoningwu3639/MegaFusion'
url_slides: ''
url_source: 'https://arxiv.org/pdf/2408.11001'
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

