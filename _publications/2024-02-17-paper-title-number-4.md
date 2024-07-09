---
title: "Meta-tuning loss functions and data augmentation for few-shot object detection"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about improving loss functions of few-shot detectors with meta-tuning.'
date: 2023-04-24
venue: 'CVPR 2023'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Demirel_Meta-Tuning_Loss_Functions_and_Data_Augmentation_for_Few-Shot_Object_Detection_CVPR_2023_paper.pdf'
citation: 'Demirel, B., Buğra Baran, O., and Gokberk Cinbis, R., “Meta-tuning Loss Functions and Data Augmentation for Few-shot Object Detection”, 2023. doi:10.48550/arXiv.2304.12161.'
---

## ABSTRACT

Few-shot object detection, the problem of modelling novel object detection categories with few training instances, is an emerging topic in the area of few-shot learning and object detection. Contemporary techniques can be divided into two groups: fine-tuning based and meta-learning based approaches. While meta-learning approaches aim to learn dedicated meta-models for mapping samples to novel class models, fine-tuning approaches tackle few-shot detection in a simpler manner, by adapting the detection model to novel classes through gradient based optimization. Despite their simplicity, fine-tuning based approaches typically yield competitive detection results. Based on this observation, we focus on the role of loss functions and augmentations as the force driving the fine-tuning process, and propose to tune their dynamics through meta-learning principles. The proposed training scheme, therefore, allows learning inductive biases that can boost few-shot detection, while keeping the advantages of fine-tuning based approaches. In addition, the proposed approach yields interpretable loss functions, as opposed to highly parametric and complex few-shot meta-models. The experimental results highlight the merits of the proposed scheme, with significant improvements over the strong fine-tuning based few-shot detection baselines on benchmark Pascal VOC and MS-COCO datasets, in terms of both standard and generalized few-shot performance metrics.
