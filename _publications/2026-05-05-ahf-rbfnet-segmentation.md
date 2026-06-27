---
title: "AHF-RBFNet: Attention-Guided Hierarchical Fusion U-Net with Learnable Fuzzy Membership Kernels for Medical Image Segmentation"
collection: publications
permalink: /publication/2026-ahf-rbfnet-segmentation
excerpt: 'Integrating a learnable Radial Basis Function (RBF) fuzzy membership kernel into a hierarchical U-Net to dynamically filter semantic uncertainty, achieving SOTA IoU on skin lesion datasets.'
date: 2026-05-05
venue: 'Active Research (Targeting Expert Systems with Applications, Q1)'
paperurl: '#'
citation: 'L. Chhetri, et al. (2026). &quot;AHF-RBFNet: Attention-Guided Hierarchical Fusion U-Net with Learnable Fuzzy Membership Kernels for Medical Image Segmentation.&quot; <i>In Progress</i>.'
---

### Project Abstract & Overview
A primary challenge in automated skin lesion and boundary segmentation is the semantic uncertainty caused by blurry boundaries and low tissue contrast. To dynamically filter this uncertainty, we engineered AHF-RBFNet by integrating a learnable Radial Basis Function (RBF) fuzzy membership kernel directly into the skip-connections of an Attention-Guided Hierarchical Fusion U-Net. This integration enables the network to explicitly model fuzzy spatial boundaries. The architecture achieves state-of-the-art performance on the ISIC 2016 dataset, yielding 84.55% IoU and 91.97% Dice metrics, strictly outperforming 11 established segmentation baselines.

### Key Methodologies & Contributions
* **Learnable Fuzzy Kernels:** Successfully combined fuzzy logic uncertainty filtering with deep representation learning, creating an explicit mathematical mechanism to handle spatial margin ambiguity in medical imaging.
* **Massive Hyperparameter Optimization:** Orchestrated large-scale hyperparameter searches utilizing Optuna to converge on robust kernel configurations.
* **Rigorous Multi-Dataset Evaluation:** Validated generalizability through extensive testing across multiple clinical datasets (ISIC, BUSI, PH2) supported by detailed 5-variant systematic ablation studies.

### Code & Resources
* Official PyTorch Implementation will be linked upon publication.