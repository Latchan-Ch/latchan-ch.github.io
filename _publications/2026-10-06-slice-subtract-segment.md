---
title: "Slice, Subtract, Segment: Efficient 2D and Physiologically Informed 3D Brain Tumor Segmentation"
collection: publications
permalink: /publication/2026-slice-subtract-segment
excerpt: 'Separating the two design levers in brain tumor segmentation (network architecture and input representation) through an efficient 2D SIBA-UNet and a controlled 3D study of cross-modal MRI subtraction maps.'
date: 2026-10-06
venue: 'bioRxiv (Preprint)'
paperurl: '#'
citation: 'L. Chhetri, A. Anand (2026). &quot;Slice, Subtract, Segment: Efficient 2D and Physiologically Informed 3D Brain Tumor Segmentation.&quot; <i>bioRxiv</i>. doi:10.64898/2026.10.04.756528.'
---

### Project Abstract & Overview
Glioma segmentation on multiparametric MRI can be improved in two ways: by changing the network architecture, or by changing the information given to the network. These two levers are usually studied together, which makes their individual effects hard to see. This preprint brings together two completed, independent studies, each of which isolates one lever. In the architecture study (Slice), SIBA-UNet, a 2D U-Net combining depthwise separable convolution, inverted-bottleneck blocks and attention-guided skip fusion, reached an overall validation Dice of 0.8601 on BraTS 2020 under a patient-level split. In the representation study (Subtract), CMSR-3D kept a 3D U-Net fixed and added four voxel-wise cross-modal subtraction maps to the standard MRI sequences. Evaluated on 1,251 BraTS-GLI 2023 cases, the full 8-channel input gave the highest mean Dice (0.87 vs. 0.86) and the lowest mean HD95 (5.99 vs. 8.23) compared with the 4-channel baseline.

### Key Methodologies & Contributions
* **Efficient 2D Architecture (SIBA-UNet):** Combined depthwise separable convolution, inverted-bottleneck blocks and attention-guided skip fusion in a slice-based U-Net, with the decision threshold selected on validation data (subregion Dice: 0.88 necrotic core, 0.85 edema, 0.91 enhancing tumor).
* **Physiologically Informed Input Representation (CMSR-3D):** Introduced four cross-modal subtraction maps (T1−T1CE, T2−FLAIR, FLAIR−T1CE, T2−T1CE) and tested 4-, 6- and 8-channel inputs with the architecture held fixed. Only the complete set of maps gave a clear gain; either half alone changed mean Dice by at most 0.0037.
* **Controlled and Transparent Reporting:** Each study changes one variable at a time, results are reported exactly as documented, and scores across the two studies are not compared directly because their datasets, dimensionality and evaluation protocols differ.

### Resources
* **Preprint:** [bioRxiv, doi:10.64898/2026.10.04.756528](https://doi.org/10.64898/2026.10.04.756528)
* **Data:** Publicly available BraTS 2020 and BraTS-GLI 2023 training data, under the BraTS challenge data-use terms.
