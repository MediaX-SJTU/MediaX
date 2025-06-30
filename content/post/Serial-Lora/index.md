---
title: '[ICME2025]Serial Low-rank Adaptation of Vision Transformer'
date: 2025-05-22
image:
  focal_point: 'top'


---

<!--more-->
Fine-tuning large pre-trained vision foundation models in a parameter-efficient manner is critical for downstream vision tasks, considering the practical constraints of computational and storage costs. Low-rank adaptation (LoRA) is a well-established technique in this domain, achieving impressive efficiency by reducing the parameter space to a low-rank form. However, developing more advanced low-rank adaptation methods to reduce parameters and memory requirements remains a significant challenge in resource-constrained application scenarios. In this study, we consider on top of the commonly used vision transformer and propose Serial LoRA, a novel LoRA variant that introduces a shared low-rank matrix serially composite with the attention mechanism. Such a design extracts the underlying commonality of parameters in adaptation, significantly reducing redundancy. Notably, Serial LoRA uses only 1/4 parameters of LoRA but achieves comparable performance in most cases. We conduct extensive experiments on a range of vision foundation models with the transformer structure, and the results confirm consistent superiority of our method.

