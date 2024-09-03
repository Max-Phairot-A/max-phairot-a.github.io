---
title: "Towards asynchronous motor imagery-based brain-computer interfaces: a joint training scheme using deep learning"
collection: publications
category: conferences
permalink: /publication/2018-10-28-MI-joint-training
excerpt: '.....'
date: 2018-10-28
venue: 'TENCON 2018 - 2018 IEEE Region 10 Conference'
# slidesurl: 'https://...'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8650546'
citation: 'P. Cheng, <b>P. Autthasan,</b> B. Pijarana, E. Chuangsuwanich and T. Wilaiprasitporn, &quot;<b>Towards Asynchronous Motor Imagery-Based Brain-Computer Interfaces: a joint training scheme using deep learning</b>&quot; in <i>TENCON 2018 - 2018 IEEE Region 10 Conference,</i> Jeju, Korea (South), 2018, pp. 1994-1998.'
---
In this paper, the deep learning (DL) approach is applied to a joint training scheme for asynchronous motor imagery-based Brain-Computer Interface (BCI). The proposed DL approach is a cascade of one-dimensional convolutional neural networks and fully-connected neural networks (CNN-FC). The focus is mainly on three types of brain responses: non-imagery EEG (background EEG), (pure imagery) EEG, and EEG during the transitional period between background EEG and pure imagery (transitional imagery). The study of transitional imagery signals should provide greater insight into real-world scenarios. It may be inferred that pure imagery and transitional EEG are high and low power EEG imagery, respectively. Moreover, the results from the CNN-FC are compared to the conventional approach for motor imagery-BCI, namely the common spatial pattern (CSP) for feature extraction and support vector machine (SVM) for classification (CSP-SVM). Under a joint training scheme, pure and transitional imagery are treated as the same class, while background EEG is another class. Ten-fold cross-validation is used to evaluate whether the joint training scheme significantly improves the performance task of classifying pure and transitional imagery signals from background EEG. Using sparse of just a few electrode channels (Cz , C3 and C4 ), mean accuracy reaches 71.52% and 70.27% for CNN-FC and CSP-SVM, respectively. On the other hand, mean accuracy without the joint training scheme achieve only 62.68% and 52.41% for CNN-FC and CSP-SVM, respectively.
