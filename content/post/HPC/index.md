---
title: '[MM2024]HPC: Hierarchical Progressive Coding Framework for Volumetric Video'
date: 2024-08-28
image:
  focal_point: 'top'
---

<!--more-->
'Volumetric video based on Neural Radiance Field (NeRF) holds vast potential for various 3D applications, but its substantial data volume poses significant challenges for compression and transmission. Current NeRF compression lacks the flexibility to adjust video quality and bitrate within a single model for various network and device capacities. To address these issues, we propose HPC, a novel hierarchical progressive volumetric video coding framework achieving variable bitrate using a single model. Specifically, HPC introduces a hierarchical representation with a multi-resolution residual radiance field to reduce temporal redundancy in long-duration sequences while simultaneously generating various levels of detail. Then, we propose an end-to-end progressive learning approach with a multi-rate-distortion loss function to jointly optimize both hierarchical representation and compression. Our HPC trained only once can realize multiple compression levels, while the current methods need to train multiple fixed-bitrate models for different rate-distortion (RD) tradeoffs. Extensive experiments demonstrate that HPC achieves flexible quality levels with variable bitrate by a single model and exhibits competitive RD performance, even outperforming fixed-bitrate models across various datasets.'

