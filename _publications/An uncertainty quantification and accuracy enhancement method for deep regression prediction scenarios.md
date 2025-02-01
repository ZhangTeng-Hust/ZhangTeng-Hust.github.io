---
title: "An uncertainty quantification and accuracy enhancement method for deep regression prediction scenarios"
collection: publications
permalink: /publication/An uncertainty quantification and accuracy enhancement method for deep regression prediction scenarios
excerpt: 'In this study, a method for uncertainty quantification and accuracy enhancement, referred to as UQAE, was proposed for deep
regression prediction scenarios, considering the relationship between point predictions and intervals. The method consists of two main components: a joint point-interval prediction module and a FIS-based accuracy enhancement module. These components comprehensively account for the point-interval similarity in joint predictions and the role of joint prediction results in calibrating point accuracy. To validate the advantages of the proposed method, three classes of datasets with nine tasks were constructed, and a fair comparison and analysis were conducted against current state-of-the-art methods. Based on the experimental results and analysis.'
date: 2025-1-20
venue: 'Jan 20'
paperurl: 'https://doi.org/10.1016/j.ymssp.2025.112394'
citation: 'Zhang, T., Peng, F., Yan, R., Tang, X., Yuan, J., & Deng, R. (2025). An uncertainty quantification and accuracy enhancement method for deep regression prediction scenarios. Mechanical Systems and Signal Processing, 227, 112394, https://doi.org/10.1016/j.ymssp.2025.112394.'
---

### Contribution

In response to the research limitations outlined above, this paper proposes an uncertainty quantification and accuracy enhancement method for deep regression prediction scenarios, named UQAE. This method takes into account the transferability of the point prediction model to the interval estimation model in the shallow parameters, as well as the accuracy enhancement of point predictions resulting from the point-interval coupling relationship. In general, the contributions of the proposed method can be summarized as follows:

1. A joint point-interval prediction module was designed. The asynchronous training strategy for the joint point-interval prediction model, which incorporates threshold monitoring and parameter sharing, enabled distribution-free joint point-interval prediction that considers epistemic uncertainty. Experimental validation demonstrated the flexible applicability of the proposed method, making it suitable for models with different structural bases, such as ANN and LSTM.
2. An accuracy enhancement strategy based on FIS was developed using the joint prediction results. The proposed point accuracy enhancement model, grounded in FIS, leveraged the point-interval relationship and realized accuracy enhancement based on joint prediction results. This was achieved through an interpretable FIS that provided secondary calibration of the initial point prediction results.
3. The advantages of the proposed method were verified using point prediction accuracy evaluation metrics, such as MAE and RMSE, as well as interval estimation evaluation metrics, including PICP and PINAW. These evaluations were conducted on synthetic datasets, UCI datasets, and a private robot pose error dataset. The proposed method achieved optimal global performance across joint evaluation metrics for both point prediction and uncertainty prediction interval estimation.

### Graphic Abstracts

The graphic abstract is shown below

![图形摘要2](..\images\paper5GA.png)

