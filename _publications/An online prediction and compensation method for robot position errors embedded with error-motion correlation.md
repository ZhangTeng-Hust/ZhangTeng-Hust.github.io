---
title: "An online prediction and compensation method for robot position errors embedded with error-motion correlation"
collection: publications
permalink: /publication/An online prediction and compensation method for robot position errors embedded with error-motion correlation
excerpt: 'Error prediction and compensation are crucial requirements for improving robot accuracy. To this end, this paper introduces an advanced online method that integrates error-motion correlation for the precise prediction and compensation of robot position errors. The proposed method includes feature selection, model interpretability design, and compensation value smoothness. Analyzing the error characteristics and designing a model based on error-motion correlation reveals that the proposed method reduces position errors by 92% and 89% at a frequency of 250 Hz in two tasks with different working conditions. This reduction in position errors ensures smoother compensation, leading to a notable improvement in accuracy for high-precision robotics applications. Unlike existing research that focuses on mapping models, the proposed method prioritizes understanding error behavior, thereby resulting in a comprehensive approach for error management in robotic systems. This contribution is invaluable for advancing the field of precision robotics and ensuring reliable performances in various robotic tasks.'
date: 2024-05-11
venue: 'May 11'
paperurl: 'https://doi.org/10.1016/j.measurement.2024.114866'
citation: 'T. Zhang, H. Sun, F. Peng, X. Tang, R. Yan, R. Deng, An online prediction and compensation method for robot position errors embedded with error-motion correlation, Measurement, (2024) 114866, https://doi.org/10.1016/j.measurement.2024.114866.'

---

### Contribution

An online prediction and compensation method for robot position errors embedded with an error-motion correlation was presented in this study. The main contributions of this study are as follows: 

1. The nature of the error-step phenomenon prevalent in robots during motion reversal was revealed and defined as the error-motion correlation by analyzing the relationship between the robot motion and position errors.
2. Based on the analyzed error-motion correlation, the method was designed considering three aspects: original feature selection, model structure interpretability design, and compensation value smoothness. The proposed method can realize error-step self-discovery, self-adjustment, and smooth compensation under the premise of accurate prediction.
3. A comparative validation of the proposed method was conducted for two tasks, ISO 9280-1998 no-load trajectory and robotic machining. The proposed method exhibits a pronounced advantage in terms of online prediction accuracy, thereby outperforming the state-of-the-art alternatives with impressive *RMSE* reductions of 66.47% and 75.93% for these tasks, respectively. The online error compensation system operated at a high frequency of 250 Hz, thereby leading to a substantial reduction in the average position errors of 92% and 89% for the aforementioned tasks. Further, the system slightly diminished the fluctuations in the compensated position errors, thereby leading to a significant enhancement in global consistency.

Based on the research conducted in this study, we will further investigate the application of the proposed method under different working conditions to adapt the robot to scenarios such as aerospace cabin segments and propellers. Further, we will consider combining a trajectory planning study with the proposed method to further optimize the robot error step phenomenon.

### Graphic Abstracts

The graphic abstract is shown below

![Paper3 GA](..\images\An online prediction and compensation method for robot position errors embedded with error-motion correlation.png)