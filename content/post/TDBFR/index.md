---
title: [ICME'2025] TD-BFR: Truncated Diffusion Model for Efficient Blind Face Restoration
date: 2025-03-01
image:
  focal_point: 'top'
---

<!--more-->
Diffusion-based methodologies have shown signifcant potential in blind face restoration (BFR), leveraging their robust generative capabilities. However, they are often criticized for two significant problems: slow training and inference speed, and inadequate recovery of fine-grained facial details. 

To address these problems, we propose a novel Truncated Diffusion model for efficient Blind Face Restoration (TD-BFR), a threestage paradigm tailored for the progressive resolution of degraded images. Specifically, TD-BFR utilizes an innovative truncated sampling method, starting from low-quality (LQ) images at low resolution to enhance sampling speed, and then introduces an adaptive degradation removal module to handle unknown
degradations and connect the generation processes across diferent resolutions. 

Additionally, we further adapt the priors of pre-trained diffusion models to recover rich facial details. Our method efficiently restores high-quality images in a coarse-to-fine manner and experimental results demonstrate that TD-BFR is, on average, 4.75× faster than current state-of-the-art diffusion based BFR methods while maintaining competitive quality.

