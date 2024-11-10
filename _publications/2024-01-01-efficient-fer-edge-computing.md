---
title: "Efficient Facial Expression Recognition Framework Based on Edge Computing" 
collection: publications 
category: manuscripts 
permalink: /publication/2024-01-01-efficient-fer-edge-computing 
excerpt: 'An efficient FER framework integrating DL with edge computing for privacy-preserving, low-latency applications.' 
date: 2024-01-01 
venue: 'Journal of Supercomputing (SJR Q2)' 
paperurl: 'https://doi.org/10.1007/s11227-023-05548-x' 
citation: 'Aikyn, N., Zhanegizov, A., Aidarov, T., Bui, D. M., & Tu, N. A. (2024). "Efficient Facial Expression Recognition Framework Based on Edge Computing." <i>Journal of Supercomputing</i>.'
---

Facial expression recognition (FER) is a technology that recognizes human emotions based on biometric markers. Over the past decade, FER has been a popular research area, particularly in the computer vision community. With deep learning (DL) development, FER can achieve impressive recognition accuracy. In addition, favorable Internet-of-Things (IoT) advancements generate massive amounts of visual data needed to enable reliable DL-based emotion analysis. However, training DL models can suffer from significant memory consumption and computational costs, complicating many vision tasks. Additionally, the direct use of RGB images during the training and inference stages might raise privacy concerns in various FER applications. On the other hand, adopting large deep networks hampers quick and accurate recognition on resource-constrained end devices such as smartphones. As a viable solution, edge computing can be employed to bring data storage and computation closer to end devices rather than relying on a central cloud server. As a result, it can potentially facilitate the deployment of real-time FER applications since the latency and efficiency problems are well addressed by utilizing the computing resources at the edge. In this paper, we develop an efficient FER framework that integrates DL with edge computing. Our framework relies on facial landmarks to enable privacy-preserving and low-latency FER. Accordingly, various landmark detection models and feature types are studied empirically to investigate their capabilities in capturing the dynamic information of facial expressions in videos. Then, using the extracted landmark-based features, we design lightweight DL models to classify human emotions on IoT devices. Extensive experiments performed on benchmark datasets further validate the efficiency and robustness of our framework.
