---
title: "Communication algorithms via deep learning"
collection: publications
permalink: /publication/2018-05-communication-algorithms-deep-learning
excerpt: "This paper demonstrates how deep learning can be used to discover new communication algorithms that outperform traditional methods."
date: 2018-05-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/1805.09317"
citation: "Kim, H., Jiang, Y., Rana, R., Kannan, S., Oh, S., & Viswanath, P. (2018). Communication algorithms via deep learning. <i>arXiv preprint arXiv:1805.09317</i>."
categories: [ai, networks]
featured: true
---

## Abstract
Coding theory is a central discipline underpinning wireline and wireless modems that are the workhorses of the information age. Progress in coding theory is largely driven by individual human ingenuity with sporadic breakthroughs over the past century. In this paper we study whether it is possible to automate the discovery of decoding algorithms via deep learning. We study a family of sequential codes parameterized by recurrent neural network (RNN) architectures. We show that creatively designed and trained RNN architectures can decode well known sequential codes such as the convolutional and turbo codes with close to optimal performance on the additive white Gaussian noise (AWGN) channel, which itself is achieved by breakthrough algorithms of our times (Viterbi and BCJR decoders, representing dynamic programing and forward-backward algorithms). We show strong generalizations, i.e., we train at a specific signal to noise ratio and block length but test at a wide range of these quantities, as well as robustness and adaptivity to deviations from the AWGN setting.

## Citation
```bibtex
@misc{kim2018communicationalgorithmsdeeplearning,
      title={Communication Algorithms via Deep Learning}, 
      author={Hyeji Kim and Yihan Jiang and Ranvir Rana and Sreeram Kannan and Sewoong Oh and Pramod Viswanath},
      year={2018},
      eprint={1805.09317},
      archivePrefix={arXiv},
      primaryClass={stat.ML},
      url={https://arxiv.org/abs/1805.09317}, 
}
```