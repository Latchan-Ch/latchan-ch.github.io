---
title: "Interpretable Solar Panel Defect Detection via Fuzzy Rule Extraction from Hierarchical Vision Models"
collection: publications
permalink: /publication/2026-solar-panel-fuzzy-rules
excerpt: 'An interpretable vision framework that automatically extracts human-readable fuzzy rules from deep visual representations for solar panel defect severity detection.'
date: 2026-08-15
venue: 'Under Review at ICVGIP, 2026'
paperurl: '#'
citation: 'L. Chhetri, A. Kumar, D. Das, P. Ghosal. (2026). &quot;Interpretable Solar Panel Defect Detection via Fuzzy Rule Extraction from Hierarchical Vision Models.&quot; <i>ICVGIP (Under Review)</i>.'
---

### Abstract
The reliability of solar energy systems depends on timely detection of photovoltaic defects, yet conventional deep learning models often provide opaque predictions that are difficult for operators to interpret. We introduce an interpretable framework that automatically extracts human-readable fuzzy rules from latent representations of deep vision models, enabling transparent defect severity prediction without manually engineered rules. Evaluated on the ELPV benchmark containing 2,624 electroluminescence images, the framework compares five modern CNN and transformer architectures. Swin-Tiny achieves the highest classification accuracy of 80.96%, while ConvNeXt-Tiny and Swin-Tiny demonstrate substantially stronger feature-severity correlations than traditional CNNs, enabling more reliable fuzzy rule extraction.

### Key Methodologies & Contributions
* **Automatic Fuzzy Rule Extraction:** Developed an end-to-end framework that converts deep visual features into human-readable IF-THEN rules without manual rule engineering.
* **Hierarchical Vision Models:** Evaluated ResNet50, EfficientNetB0, ConvNeXt-Tiny, ViT-Tiny, and Swin-Tiny to study how backbone architecture affects interpretability.
* **Feature-Severity Analysis:** Used Pearson correlation to identify severity-discriminative latent features and generate interpretable fuzzy membership functions.
* **Explainable Defect Detection:** Combined deep classifier predictions with fuzzy rule confidence and Grad-CAM/attention analysis to provide transparent solar defect severity predictions.
* **ELPV Benchmark:** Evaluated the proposed methodology on 2,624 electroluminescence images across no-defect, mild-defect, and severe-defect categories.

### Publication Status
**Under Review at ICVGIP, 2026**

**Authors:** L. Chhetri, A. Kumar, D. Das, P. Ghosal

### Code & Resources
* [Official PyTorch Implementation (GitHub)](https://github.com/HaloMind-Research/Interpretable-Solar-Defect-Detection)
