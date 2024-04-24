---
title: "An active semi-supervised transfer learning method for robot pose error prediction and compensation"
collection: publications
permalink: /publication/An active semi-supervised transfer learning method for robot pose error prediction and compensation
excerpt: 'In this work, an active semi-supervised transfer learning method (ASTL) is proposed for accurate and efficient prediction and compensation of robot pose error by integrating the multi-stage greedy sampling (MGS) and the semi-supervised transfer learning (STL). The robot pose error prediction problem is defined as a transfer learning paradigm for the first time in this work, where theoretical knowledge of pose error distribution is embedded into the simulation domain through coarse calibration and a few samples are selected and measured by the MGS to form the high precision measurement domain. The knowledge of the simulation domain is transferred to the measurement domain in the form of model, data, and loss function by the proposed semi- supervised transfer learning (STL), which achieves a high accuracy of pose error prediction. The performance of ASTL was compared with other sample selection strategies and prediction algorithms on the four tasks constructed (POINTS, LINE, CURVE and SURFACE). The results show the accurate and efficient performance of ASTL, which is meaningful for future robotic high-precision applications.'
date: 2023-11-07
venue: 'November 11'
paperurl: 'https://doi.org/10.1016/j.engappai.2023.107476'
citation: 'T. Zhang, F. Peng, X. Tang, R. Yan, C. Zhang, R. Deng, An active semi-supervised transfer learning method for robot pose error prediction and compensation, Eng. Appl. Artif. Intell., 128 (2024) 107476, https://doi.org/10.1016/j.engappai.2023.107476.'
---

### Contribution

Aiming at the limited efficiency and accuracy of existing robot position error prediction methods, by combining limited sample labelling and high-precision error prediction, an active semi-supervised transfer learning (ASTL) method is proposed in this paper. Based on a detailed experimental comparison and analysis, the conclusions of this study are as follows:

1. The robot pose error prediction problem is defined as a transfer learning paradigm for the first time. The simulation domain based on coarse calibration and the measurement domain based on measurements were examined simultaneously. Knowledge is transferred and shared between the two domains.
2. Multi-stage greedy sampling (MGS) is proposed to achieve informed sample selection and labelling, which significantly reduces the labelling cost while improving the quality of the samples involved in model training. Semi-supervised transfer learning (STL) methods are designed to achieve knowledge transfer from the simulation domain to the measurement domain in terms of the model, data, and loss functions to ensure model accuracy.
3. Four robot motion tasks are designed to validate the effects of the ASTL. Among the comparisons with other sample selection and transfer learning methods, ASTL exhibited the best performance. After using the ASTL, the average error prediction efficiency improved by approximately 89% and the maximum robot error reduction was approximately 90%.

The proposed ASTL method is efficient and accurate for robot pose error prediction and compensation, which significantly improves the usability of the algorithm in solving practical engineering problems, and can provide an effective prediction and compensation method for high-precision robotic application scenarios.

### Graphic Abstracts

The graphic abstract is shown below

![Paper3 GA](..\images\paper3 GA.png)
