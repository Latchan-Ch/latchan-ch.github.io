---
title: "Degraded Ancient Ashokan Brahmi Script Recognition via Self-Supervised Pretraining and WGAN-GP Degradation Pipelines"
collection: publications
permalink: /publication/2026-brahmi-script-ocr
excerpt: 'An end-to-end OCR and visual inpainting framework for ancient Indic scripts, introducing a 150K sequence dataset generated via physically-motivated WGAN-GP degradation.'
date: 2026-05-10
venue: 'Active Research (Targeting ICDAR 2027)'
paperurl: '#'
citation: 'L. Chhetri, et al. (2026). &quot;Degraded Ancient Ashokan Brahmi Script Recognition via Self-Supervised Pretraining and WGAN-GP Degradation Pipelines.&quot; <i>In Progress</i>.'
---

### Project Abstract & Overview
Deciphering highly degraded ancient scripts is severely bottlenecked by a lack of clean, annotated data. Serving as the Computer Vision and Machine Learning Lead, I am directing a research team to build an end-to-end optical character recognition (OCR) and document analysis pipeline for ancient Ashokan Brahmi script. We engineered a massive data generation pipeline leveraging WGAN-GP to synthesize 20K+ unique character forms, subjected to physically-motivated degradation modeling to build a comprehensive 150K sequence training dataset.

### Key Methodologies & Contributions
* **Synthetic-to-Real Domain Gap Study:** Established the first severity-based Character Error Rate (CER) evaluation benchmark for ancient Indic scripts, isolating how physical stone degradation impacts text decoding.
* **Self-Supervised OCR Architecture:** Developed an efficient architecture integrating SimCLR self-supervised pretraining on a ResNet34 backbone, coupled with a bidirectional LSTM and Connectionist Temporal Classification (BiLSTM-CTC) decoder.
* **Team Leadership:** Spearheading the research vision, designing ETL pipelines, and mentoring student collaborators through data curation and model optimization phases.

### Code & Resources
* Official PyTorch Implementation will be linked upon publication.