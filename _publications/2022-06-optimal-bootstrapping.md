---
title: "Optimal bootstrapping of PoW blockchains"
collection: publications
permalink: /publication/2022-06-optimal-bootstrapping
excerpt: "This work presents optimal strategies for bootstrapping proof-of-work blockchains with security guarantees."
date: 2022-06-01
venue: "Proceedings of the Twenty-Third International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing"
paperurl: "https://dl.acm.org/doi/abs/10.1145/3492866.3549731"
citation: "Rana, R., Karakostas, D., Kannan, S., Kiayias, A., & Viswanath, P. (2022). Optimal bootstrapping of pow blockchains. In Proceedings of the Twenty-Third International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing (pp. 81-90)."
categories: [blockchain, security]
---

## Abstract
Proof of Work (PoW) blockchains are susceptible to adversarial majority mining attacks in the early stages due to incipient participation and corresponding low net hash power. Bootstrapping ensures safety and liveness during the transient stage by protecting against a majority mining attack, allowing a PoW chain to grow the participation base and corresponding mining hash power. Liveness is especially important since a loss of liveness will lead to loss of honest mining rewards, decreasing honest participation, hence creating an undesired spiral; indeed existing bootstrapping mechanisms offer especially weak liveness guarantees.
In this paper, we propose Advocate, a new bootstrapping methodology, which achieves two main results: (a) optimal liveness and low latency under a super-majority adversary for the Nakamoto longest chain protocol and (b) immediate black-box generalization to a variety of parallel-chain based scaling architectures, including OHIE and Prism. We demonstrate via a full-stack implementation the robustness of Advocate under a 90% adversarial majority.
## Citation
```bibtex
@inproceedings{rana2022optimal,
  title={Optimal bootstrapping of pow blockchains},
  author={Rana, Ranvir and Karakostas, Dimitris and Kannan, Sreeram and Kiayias, Aggelos and Viswanath, Pramod},
  booktitle={Proceedings of the Twenty-Third International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing},
  pages={231--240},
  year={2022}
}
```