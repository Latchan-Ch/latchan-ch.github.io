---
title: "Attention-Enhanced Swin Transformers for Robust Brain Tumor Classification Under Patient-Level Data Splitting"
collection: publications
permalink: /publication/2026-swin-brain-tumor
excerpt: 'We propose an Attention-Enhanced Swin Transformer integrating hierarchical windowed attention with CBAM to mitigate data leakage, achieving 96.82% accuracy on strict patient-level splits.'
date: 2026-06-05
venue: 'Accepted at IEEE GCON'
paperurl: 'https://github.com/Latchan-Ch/Robust-Swin-Brain-Tumor'
citation: 'L. Chhetri, P. Ghosal, A. Datta. (2026). &quot;Attention-Enhanced Swin Transformers for Robust Brain Tumor Classification Under Patient-Level Data Splitting.&quot; <i>IEEE GCON</i>.'
---

### Abstract
Contemporary brain tumor classification systems report accuracies exceeding 98%, yet such metrics are artificially inflated by dataset partitioning flaws. Conventional image-level splitting allows identical patient scans in both training and testing sets, enabling networks to memorize patient-specific features rather than tumor patterns. We enforce patient-level separation where each patient remains in a single partition. Evaluation of five architectures reveals degradations reaching 3.71% under patient-level splitting, validating widespread data leakage. We propose an Attention-Enhanced Swin Transformer integrating hierarchical windowed attention with Convolutional Block Attention Modules. Our architecture achieves 96.82% accuracy with 1.23% degradation—the smallest gap among methods. Gradient-weighted activation mapping confirms attention on tumor regions rather than anatomical artifacts, establishing reliable feature extraction for trustworthy medical AI.

### Key Methodologies & Contributions
* **Exposing Data Leakage**: We demonstrated that conventional 70/15/15 random partitioning creates cross-patient contamination, artificially boosting accuracy metrics in baseline models.
* **Strict Patient-Level Partitioning**: We utilized the Figshare Brain Tumor MRI dataset and organized scans strictly by patient identity, guaranteeing each patient's data is isolated to a single partition for genuine clinical generalization.
* **Attention-Enhanced Backbone**: We integrated Convolutional Block Attention Modules (CBAM) into a Swin foundation backbone to prevent shortcut learning.
* **Dual-Stage Feature Refinement**: We utilized sequential channel and spatial attention to explicitly prioritize tumor-discriminative features while suppressing patient-specific anatomical signatures (e.g., skull boundaries and ventricular configurations).

### Code & Resources
* [Official PyTorch Implementation (GitHub)](https://github.com/Latchan-Ch/Robust-Swin-Brain-Tumor)