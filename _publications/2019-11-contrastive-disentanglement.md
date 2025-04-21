---
title: "Towards principled objectives for contrastive disentanglement"
collection: publications
permalink: /publication/2019-11-contrastive-disentanglement
excerpt: "A novel approach to disentangled representation learning using contrastive methods with theoretical foundations."
date: 2019-11-01
venue: "arXiv preprint"
paperurl: "https://openreview.net/pdf?id=B1lPETVFPS"
citation: "Choudhuri, A., Makkuva, A. V., Rana, R., Oh, S., Chowdhary, G., & Schwing, A. (2019). Towards principled objectives for contrastive disentanglement. arXiv preprint arXiv:1911.11561."
categories: [ai, machine-learning]
---

## Abstract
Unsupervised learning is an important tool that has received a significant amount of attention for decades. Its goal is "unsupervised recovery," i.e., extracting salient factors/properties  from unlabeled data. Because of the challenges in defining salient properties, recently, "contrastive disentanglement" has gained popularity to discover the additional variations that are enhanced in one dataset relative to another. %In fact, contrastive disentanglement and unsupervised recovery are often combined in that we seek additional variations that exhibit salient factors/properties. 
Existing formulations have devised a variety of losses for this task. However, all present day methods exhibit two major shortcomings: (1) encodings for data that does not exhibit salient factors is not pushed to carry no signal; and (2) introduced losses are often hard to estimate and require additional trainable parameters. We present a new formulation for contrastive disentanglement which avoids both shortcomings by carefully formulating a probabilistic model and by using non-parametric yet easily computable metrics. We show on four challenging datasets that the proposed approach is able to better disentangle salient factors.

## Citation
```bibtex
@misc{
choudhuri2020towards,
title={Towards Principled Objectives for Contrastive Disentanglement},
author={Anwesa Choudhuri and Ashok Vardhan Makkuva and Ranvir Rana and Sewoong Oh and Girish Chowdhary and Alexander Schwing},
year={2020},
url={https://openreview.net/forum?id=B1lPETVFPS}
}
```