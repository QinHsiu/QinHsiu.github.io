---
title: "Intent Contrastive Learning with Cross Subsequences for Sequential Recommendation"
collection: publications
permalink: /publication/2024-03-08-paper-title-number-3
excerpt: ' Intent contrastive learning with Cross Subsequences
for sequential Recommendation (ICSRec) is proposed to model
users’ latent intentions.'
date: 2024-03-08
venue: 'WSDM'
# paperurl: 'https://arxiv.org/pdf/2310.14318.pdf'
citation: 'Qin, Xiuyuan, Huanhuan Yuan, Pengpeng Zhao, Guanfeng Liu, Fuzhen Zhuang, and Victor S. Sheng. "Intent Contrastive Learning with Cross Subsequences for Sequential Recommendation." arXiv preprint arXiv:2310.14318 (2023)'
---

| Title| Year |Resources|
| ------- | ----- | ------ |
|Intent Contrastive Learning with Cross Subsequences for
Sequential Recommendation|WSDM2024|[[Paper]](https://arxiv.org/pdf/2310.14318.pdf) ,[[Code]](https://github.com/QinHsiu/ICSRec?tab=readme-ov-file) ,[[Video]](https://www.bilibili.com/video/BV1Aw411g7xC/?vd_source=96ebb649d074a7680a8f9de2c1275ed6) ,[[Note]](https://juejin.cn/post/7298220509127458843)|

Abstract
- The user purchase behaviors are mainly influenced by their intentions (e.g., buying clothes for decoration, buying brushes for
painting, etc.). Modeling a user’s latent intention can significantly
improve the performance of recommendations. Previous works
model users’ intentions by considering the predefined label in auxiliary information or introducing stochastic data augmentation to
learn purposes in the latent space. However, the auxiliary information is sparse and not always available for recommender systems,
and introducing stochastic data augmentation may introduce noise
and thus change the intentions hidden in the sequence. Therefore,
leveraging user intentions for sequential recommendation (SR) can
be challenging because they are frequently varied and unobserved.
In this paper, Intent contrastive learning with Cross Subsequences
for sequential Recommendation (ICSRec) is proposed to model
users’ latent intentions. Specifically, ICSRec first segments a user’s
sequential behaviors into multiple subsequences by using a dynamic
sliding operation and takes these subsequences into the encoder to
generate the representations for the user’s intentions. To tackle the
problem of no explicit labels for purposes, ICSRec assumes different
subsequences with the same target item may represent the same
intention and proposes a coarse-grain intent contrastive learning to
push these subsequences closer. Then, fine-grain intent contrastive
learning is mentioned to capture the fine-grain intentions of subsequences in sequential behaviors. Extensive experiments conducted
on four real-world datasets demonstrate the superior performance
of the proposed ICSRec1 model compared with baseline methods.


Recommended citation:
- Qin, Xiuyuan, Huanhuan Yuan, Pengpeng Zhao, Guanfeng Liu, Fuzhen Zhuang, and Victor S. Sheng. "Intent Contrastive Learning with Cross Subsequences for Sequential Recommendation." arXiv preprint arXiv:2310.14318 (2023).
