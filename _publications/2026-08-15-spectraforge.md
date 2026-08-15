---
title: "SPECTRAFORGE: Domain-Equalized Frequency-Spatial Fusion for Synthetic Dermatology Detection"
collection: publications
permalink: /publication/2026-spectraforge
excerpt: 'A domain-equalized dual-stream CNN framework for robust synthetic dermatology detection, achieving 0.9971 AUC and 0.9277 OOD AUC.'
date: 2026-08-15
venue: 'Accepted at IEEE DSAA (Core A-Tier), 2026'
paperurl: '#'
citation: 'A. Kumar*, L. Chhetri*, D. Das*.(2026). &quot;SPECTRAFORGE: Domain-Equalized Frequency-Spatial Fusion for Synthetic Dermatology Detection.&quot; <i>IEEE International Conference on Data Science and Advanced Analytics (DSAA)</i>.'
---

### Abstract
Spatial deepfake detectors in medical imaging often exploit dataset-level artifacts rather than authentic generative fingerprints, leading to severe performance degradation on unseen generators. We introduce SPECTRAFORGE, a two-stream CNN framework that decouples spatial morphology from frequency-domain synthetic artifacts. A Gaussian-bottlenecked spatial stream captures lesion morphology, while a parallel FFT-magnitude stream targets periodic upsampling artifacts from diffusion decoders. An Extreme Equalizer preprocessing pipeline is used to eliminate spatial dataset leakage before feature extraction. On a controlled 2,000-image forensic cohort, SPECTRAFORGE achieves an AUC of 0.9971 ± 0.0016 and Precision of 0.9931 ± 0.0056. Under cross-checkpoint OOD evaluation, SPECTRAFORGE maintains an AUC of 0.9277 compared with 0.5494 for EfficientNet-B0, demonstrating substantially stronger domain generalization.

### Key Methodologies & Contributions
* **Extreme Equalizer Preprocessing:** Developed an in-memory preprocessing pipeline using grayscale conversion, border cropping, and Gaussian filtering to reduce dataset-level spatial leakage and artifact biases.
* **Dual-Stream CNN Architecture:** Designed parallel spatial and frequency streams using a Gaussian-bottlenecked morphology pathway and an FFT-magnitude pathway for synthetic artifact detection.
* **Robust OOD Generalization:** Achieved an OOD AUC of 0.9277 under cross-checkpoint evaluation, substantially outperforming the EfficientNet-B0 baseline.
* **High-Precision Forensic Detection:** Achieved 0.9971 ± 0.0016 AUC and 0.9931 ± 0.0056 Precision across three-seed cross-validation on a controlled 2,000-image cohort.

### Publication Status
**Accepted at IEEE DSAA, 2026 — CORE A Tier**

**Authors:** A. Kumar*, L. Chhetri*, D. Das*  
*Equal Contribution

### Code & Resources
* [Official PyTorch Implementation (GitHub)](https://github.com/HaloMind-Research/SPECTRAFORGE)

