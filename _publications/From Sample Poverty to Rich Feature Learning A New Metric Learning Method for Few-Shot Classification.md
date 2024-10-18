---
title: "From Sample Poverty to Rich Feature Learning: A New Metric Learning Method for Few-Shot Classification"
collection: publications
category: manuscripts
permalink: /publication/From Sample Poverty to Rich Feature Learning A New Metric Learning Method for Few-Shot Classification
excerpt: 'IF:3.4  SCIE  JCR-Q2  中科院3区  EI  \(2024\)'
date: 2024-08-16
venue: 'IEEE Access'
# slidesurl: 'https://donotwanttogrowup.github.io/YitingLin.github.io/files/slides1.pdf'
paperurl: 'https://donotwanttogrowup.github.io/files/From_Sample_Poverty_to_Rich_Feature_Learning_A_New_Metric_Learning_Method_for_Few-Shot_Classification.pdf'
citation: 'Zhang, L., Lin, Y., Yang, X., Chen, T., Cheng, X., & Cheng, W. (2024). From Sample Poverty to Rich Feature Learning: A New Metric Learning Method for Few-Shot Classification. In IEEE Access (Vol. 12, pp. 124990–125002). Institute of Electrical and Electronics Engineers (IEEE). https://doi.org/10.1109/access.2024.3444483
'
---

With the rapid development of deep learning in the field of computer vision, few-shot learning has emerged as an effective approach to tackle the challenge of data scarcity, garnering widespread attention from researchers. Despite significant progress in few-shot learning, current few-shot image classification methods have not fully exploited the feature extraction capabilities of the backbone network and the existing labeled data. To address this issue, we introduces a few-shot image classification method based on metric learning, which aims to more fully explore and utilize these resources. During training, we employed the PatchUp technique to perform block-level operations in the hidden layer feature space, obtaining more diverse feature representations, thereby expanding the range of data representation and aiding in the formation of smoother classification decision boundaries. Additionally, the introduction of a self-supervised auxiliary loss helps the network to learn deep semantic information stably, thereby enhancing the classification performance for new categories. Furthermore, the centralization and normalization of features extracted by the backbone network significantly enhance the model’s performance in few-shot image classification tasks. This paper conducted extensive experiments on multiple public datasets (including miniImageNet, tieredImageNet, FC-100, and CUB-200-2011), demonstrating the effectiveness and superior performance of the proposed method. The experimental results show that the method significantly improves the model’s classification accuracy and generalization ability in the 1-shot learning scenario, providing strong support for further research and application in the field of few-shot learning.