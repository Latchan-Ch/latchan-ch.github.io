---
title: "Intrinsic Neural Firewalls for Cyber-Physical Systems: Robust Anomaly Rejection via Deep Delta Residual Overwrites"
collection: publications
permalink: /publication/2026-intrinsic-neural-firewalls
excerpt: 'An intrinsic defense architecture (DDL-FW) for Cyber-Physical Systems that embeds anomaly detection directly into residual connections, achieving an F1 score of 0.7206 on the HAI 21.03 benchmark.'
date: 2026-06-07
venue: 'Under Review at WIN 6.0'
paperurl: '#'
citation: 'R. Das, L. Chhetri, A. Kumar, P. Ghosal. (2026). &quot;Intrinsic Neural Firewalls for Cyber-Physical Systems: Robust Anomaly Rejection via Deep Delta Residual Overwrites.&quot; <i>WIN 6.0 (Under Review)</i>.'
---

### Abstract
Modern Industrial Cyber-Physical Systems heavily leverage Web 6.0 communication fabrics, thus creating a practical opportunity for False Data Injection Attacks (FDIA). External detectors suffer from latencies, need pre-labeled attack data, and cannot prevent internal corruption of the state. This work proposes Deep Delta Learning Firewall (DDL-FW), an intrinsic defense architecture designed specifically for CPS, which is not dependent on any attack examples during training. DDL-FW integrates the defense functionality directly in the residual connections, substituting a simple addition of the residual to the state vector with a depth-wise read-compare-write routine, based on the principles of Deep Delta Learning (DDL). Experiments conducted using the benchmark of HAI 21.03 (79 sensors) show DDL-FW exhibits an F1 score of 0.7206 and a false positive rate of 2.01%, outperforming Isolation Forest and One-Class SVM with only 1.3M parameters.

### Key Methodologies & Contributions
* **Intrinsic Architectural Defense:** Bypassed traditional post-hoc external detectors by embedding defense functionality directly into the residual dynamics, preventing adversarial feature propagation at the architectural level.
* **Zero-Cost Anomaly Scoring:** Engineered the network to generate anomaly scores as a free byproduct of the forward pass, calculating the accumulation of residual errors through layers without adding computational overhead.
* **Attack-Agnostic (Zero-Shot) Training:** Designed the model to train exclusively on clean sequences of observations, allowing it to detect zero-day False Data Injection Attacks without needing prior exposure to malicious signatures.
* **Expanded-State Memory Quarantine:** Implemented a persistent memory matrix (d_v = 4) that physically isolates and contains adversarial contamination at layer borders, preventing noise from corrupting the global memory stream.

### Code & Resources
* Code repository will be made available upon publication and conclusion of the double-blind review process.