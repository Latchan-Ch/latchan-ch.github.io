---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

**Download my full academic CV here:** [**Download CV**]({{ site.url }}{{ site.baseurl }}/files/Latchan_CV.pdf)

---

## Education

* **B.Tech, Computer Science & Engineering (Artificial Intelligence & Data Science)**

  * Manipal Institute of Technology (Sikkim), Sikkim Manipal University, Sikkim, India
  * Jul 2023 – Jun 2027

* **ISC (Class XII), Science**

  * St. Xavier's School, West Bengal, India
  * 2023

---

## Experience

 **Research Intern, CVPR Unit** | *Jun 2026 – Present*

  * *Indian Statistical Institute, Kolkata (jointly with the University of Salford, UK) | Hybrid*
  * Supervisors: Prof. Umapada Pal (ISI Kolkata) and Prof. Shivakumara Palaiahnakote (University of Salford)
  * Working on recognition of licence plates that are bent, buckled, torn or partly covered, where standard OCR models fail badly on real damaged images. The core question is when the visible character evidence is enough to correct the geometry, and when the information is truly lost.
  * Developing a recognition-guided feedback loop that corrects local geometry only when the remaining character evidence supports it, and returns candidates with uncertainty when it does not. Designed experiments to separate deformation errors from missing-information errors before building the full model.
  * Benchmarked multiple recognizers (PARSeq, LPRNet, TrOCR, PaddleOCR, Qwen2.5-VL, etc.) on a manually verified set of crash-damaged plates. The VLM had the lowest character error rate (0.49) but read zero plates fully correctly: it stopped at folds and substituted plausible-looking characters for damaged ones.
  * Building a Blender-based synthetic generator to supply dense deformation, damage and visibility ground truth, and collected a manually verified real damaged-plate test set.

 **Research Collaborator, Remote Sensing & EO Vision** | *Sep 2026 – Present*

  * *Prof. Swalpa Kumar Roy (Tezpur University) and Dr. Saurabh Kaushik (University of Wisconsin–Madison) | Hybrid*
  * Adapting pretrained Earth-observation foundation models (e.g., THOR) to downstream tasks, modifying architectures and fine-tuning strategy for semantic segmentation and localization in satellite imagery.
  * Setting up a multi-dataset evaluation across optical satellite benchmarks to test how well foundation-model features transfer between sensors, resolutions and regions, rather than tuning to a single benchmark.
  * Reproducing recently published remote sensing models from their released code to establish trustworthy baselines, after finding that several reported results could not be reproduced.

 **Research Assistant, Satellite AI & Causal Inference** | *Jun 2026 – Present*

  * *AI & Global Development Lab (AIDevLab), UT Austin / Chalmers University | Remote*
  * Supervisors: Prof. Connor T. Jerzak (UT Austin) and Prof. Adel Daoud (Chalmers University)
  * Studying how conformal prediction intervals behave when a satellite-imagery poverty model is moved to a new region; showing that standard intervals lose their coverage under large geographic shift.
  * Wrote the data loaders for continuous International Wealth Index (IWI) regression and set up baselines and coverage metrics for geographic hold-outs, for example training on African data and testing outside the continent.

 **Founder & Lead Researcher** | *Jan 2026 – Present*

  * *Halo Mind Research Group | Onsite*
  * Started and run a small group of undergraduate researchers working on efficient vision architectures and reliable evaluation. Group work includes the DSAA 2026 and ICCI 2026 papers and the bioRxiv brain tumor segmentation preprint.
  * Set research directions, plan experiments, review code, and write papers with junior members. As senior author on the ICCI paper, I supervised a seven-person team from idea to oral presentation. Currently preparing a CVPR 2027 submission.

 **Research Assistant & Team Lead** | *Jul 2025 – Jul 2026*

  * *Sikkim Manipal Institute of Technology | Onsite*
  * Showed that image-level train/test splits inflate brain tumor classification accuracy by up to 3.71%. Proposed a Swin Transformer with CBAM attention that reached 96.82% accuracy under patient-level splitting and had the smallest leakage gap of five models (IEEE GCON 2026).
  * Ran controlled preprocessing experiments on 3,064 MRI scans from 233 patients. Found that skull stripping and CLAHE hurt accuracy while bilateral filtering with augmentation reached 93.86% (AUC 0.991) (IEEE GCON 2026).
  * Engineered Intrinsic Neural Firewalls utilizing Deep Delta Residual Overwrites for edge-deployed cyber-physical systems. Achieved high-performance, zero-shot anomaly rejection against False Data Injection Attacks (WIN 6.0).
  * Directed and mentored student research teams, training junior researchers in core deep learning methodologies and guiding end-to-end experimental design from conceptualization to multiple first-author and co-authored acceptances in IEEE, Springer and T&F venues.

 **AI & Data Science Intern** | *Jul 2025 – Aug 2025*

  * *Soft Nexis Technology | Remote*
  * Engineered and deployed RealVisor, an end-to-end AI real estate platform. Developed robust predictive pipelines utilizing XGBoost and Random Forest Regressors to estimate property valuations based on complex spatial features.
  * Conducted rigorous evaluation across curated real-world datasets, strictly outperforming baseline models, and designed a production-ready Streamlit dashboard featuring interactive market trend visualizations and automated investment analysis.

---

## Honors, Certifications & Academic Service

* **Technical Peer Reviewer (ICVGIP 2026):** Nominated and invited by Program Chairs to evaluate research manuscripts for the Indian Conference on Computer Vision, Graphics and Image Processing (Published by ACM ICPS / supported by IUPRAI).

* **Technical Peer Reviewer (IEEE GCON 2026):** Invited official peer reviewer evaluating submissions in applied deep learning, medical imaging, and computer vision architectures for IEEE GCON.

* **NPTEL Elite + Gold, Topper (Top 1%):** Introduction to Internet of Things, IIT Kharagpur. Scored 91%; top 1% of 50,282 certified candidates.

* **Online Coursework:** Deep Learning with PyTorch for Medical Image Analysis (Udemy); Introduction to Applied Machine Learning (Amii, via Coursera); Natural Language Processing with Deep Learning in Python (Udemy); Data Science & AI Masters (Udemy).

---

## Technical Skills

* **Languages:** Python, C, Java, LaTeX

* **Deep Learning:** PyTorch, TensorFlow/Keras, Optuna

* **Architectures:** CNNs, Vision Transformers, State-Space Models (Mamba), U-Net variants, GANs, Diffusion Models, VLMs, Foundation Models

* **Methods:** Segmentation, Detection, Classification, OCR, Self-Supervised Learning, Conformal Prediction, OOD Evaluation, Explainable AI, Interpretability

* **Data & Tools:** NumPy, Pandas, SciPy, Scikit-Learn, Blender, ETL Workflows, Hadoop, Spark, spaCy, NLTK, Git, Streamlit
