---
title: '[WACV 2025]MegaFusion: Extend Diffusion Models towards Higher-resolution Image Generation without Further Tuning'
date: 2024-08-18
image:
  focal_point: 'top'


---
<!--more-->
Diffusion models have emerged as frontrunners in text-to-image generation, but their fixed image resolution during training often leads to challenges in high-resolution image generation, such as semantic deviations and object replication. This paper introduces MegaFusion, a novel approach that extends existing diffusion-based text-to-image models towards efficient higher-resolution generation without additional fine-tuning or adaptation. Specifically, we employ an innovative truncate and relay strategy to bridge the denoising processes across different resolutions, allowing for high-resolution image generation in a coarse-to-fine manner. Moreover, by integrating dilated convolutions and noise re-scheduling, we further adapt the model's priors for higher resolution. The versatility and efficacy of MegaFusion make it universally applicable to both latent-space and pixel-space diffusion models, along with other derivative models. Extensive experiments confirm that MegaFusion significantly boosts the capability of existing models to pro-duce images of megapixels and various aspect ratios, while only requiring about 40% of the original computational cost. '
