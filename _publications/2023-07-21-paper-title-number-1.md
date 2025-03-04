---
title: "Meta-optimized Contrastive Learning for Sequential Recommendation"
collection: publications
permalink: /publication/2023-07-21-paper-title-number-1
excerpt: 'A more general CL-based recommendation model called Meta-optimized Contrastive Learning for sequential Recommendation (MCLRec) is proposed in this work.'
date: 2023-07-21
venue: 'SIGIR'
# paperurl: 'https://github.com/QinHsiu/MCLRec/blob/main/pdf/SIGIR2023_MCLRec.pdf'
citation: ' Xiuyuan Qin, Huanhuan Yuan, Pengpeng Zhao, Junhua Fang, Fuzhen Zhuang,
Guanfeng Liu, Yanchi Liu, and Victor S. Sheng. 2023. Meta-optimized Contrastive
Learning for Sequential Recommendation. In SIGIR. 89–98.'
---

|Title|Year|Resources|
| ------- | ----- | ------ |
|Meta-optimized Contrastive Learning for Sequential Recommendation|SIGIR 2023|[[Paper]](https://github.com/QinHsiu/MCLRec/blob/main/pdf/SIGIR2023_MCLRec.pdf) ,[[Code]](https://github.com/QinHsiu/MCLRec) ,[[Video]](https://www.bilibili.com/video/BV1sa4y1F7Jb/?spm_id_from=333.999.list.card_archive.click) ,[[Note]](https://juejin.cn/post/7289662476730368060)|

Abstract: 
- Contrastive Learning (CL) performances as a rising approach to address the challenge of sparse and noisy recommendation data. Although having achieved promising results, most existing CL methods only perform either hand-crafted data or model augmentation for generating contrastive pairs to find a proper augmentation operation for different datasets, which makes the model hard to generalize. Additionally, since insufficient input data may lead the encoder to learn collapsed embeddings, these CL methods expect a relatively large number of training data (e.g., large batch size or memory bank) to contrast. However, not all contrastive pairs are always informative and discriminative enough for the training processing. Therefore, a more general CL-based recommendation model called Meta-optimized Contrastive Learning for sequential Recommendation (MCLRec) is proposed in this work. By applying both data augmentation and learnable model augmentation operations, this work innovates the standard CL framework by contrasting data and model augmented views for adaptively capturing the informative features hidden in stochastic data augmentation. Moreover, MCLRec utilizes a meta-learning manner to guide the updating of the model augmenters, which helps to improve the quality of contrastive pairs without enlarging the amount of input data. Finally, a contrastive regularization term is considered to encourage the augmentation model to generate more informative augmented views and avoid too similar contrastive pairs within the meta updating. The experimental results on commonly used datasets validate the effectiveness of MCLRec.

Recommended citation: 
- Xiuyuan Qin, Huanhuan Yuan, Pengpeng Zhao, Junhua Fang, Fuzhen Zhuang,
Guanfeng Liu, Yanchi Liu, and Victor S. Sheng. 2023. Meta-optimized Contrastive
Learning for Sequential Recommendation. In SIGIR. 89–98..




