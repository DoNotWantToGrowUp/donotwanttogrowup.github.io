---
title: "Few-Shot Image Classification Algorithm Based on Global–Local Feature Fusion"
collection: publications
category: manuscripts
permalink: /publication/Few-Shot Image Classification Algorithm Based on Global–Local Feature Fusion
excerpt: 'IF:5.0  ESCI  JCR-Q2  中科院4区  \(2025\)'
date: 2025-10-09
venue: 'AI'
# slidesurl: 'https://donotwanttogrowup.github.io/files/slides1.pdf'
paperurl: 'https://donotwanttogrowup.github.io/files/Few-Shot Image Classification Algorithm Based on Global–Local Feature Fusion.pdf'
citation: 'Zhang, L., Yang, X., Cheng, X., Cheng, W., & Lin, Y. (2025). Few-Shot Image Classification Algorithm Based on Global–Local Feature Fusion. AI, 6(10), 265. https://doi.org/10.3390/ai6100265
'
---

Few-shot image classification seeks to recognize novel categories from only a handful of labeled examples, but conventional metric-based methods that rely mainly on global image features often produce unstable prototypes under extreme data scarcity, while local-descriptor approaches can lose context and suffer from inter-class local-pattern overlap. To address these limitations, we propose a Global–Local Feature Fusion network that combines a frozen, pretrained global feature branch with a self-attention based multi-local feature fusion branch. Multiple random crops are encoded by a shared backbone (ResNet-12), projected to Query/Key/Value embeddings, and fused via scaled dot-product self-attention to suppress background noise and highlight discriminative local cues. The fused local representation is concatenated with the global feature to form robust class prototypes used in a prototypical-network style classifier. On four benchmarks, our method achieves strong improvements: Mini-ImageNet 70.31% ± 0.20 (1-shot)/85.91% ± 0.13 (5-shot), Tiered-ImageNet 73.37% ± 0.22/87.62% ± 0.14, FC-100 47.01% ± 0.20/64.13% ± 0.19, and CUB-200-2011 82.80% ± 0.18/93.19% ± 0.09, demonstrating consistent gains over competitive baselines. Ablation studies show that (1) naive local averaging improves over global-only baselines, (2) self-attention fusion yields a large additional gain (e.g., +4.50% in 1-shot on Mini-ImageNet), and (3) concatenating global and fused local features gives the best overall performance. These results indicate that explicitly modeling inter-patch relations and fusing multi-granularity cues produces markedly more discriminative prototypes in few-shot regimes.