---
title: "Free2Shard: Adaptive-adversary-resistant sharding via dynamic self allocation"
collection: publications
permalink: /publication/2020-05-free2shard-arXiv
excerpt: "Free2Shard sharding protocol with theoretical optimality analysis and systems architecture. "
date: 2020-05-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/pdf/2005.09610"
citation: "Rana, R., Kannan, S., Tse, D., & Viswanath, P. (2020). Free2Shard: Adaptive-adversary-resistant sharding via dynamic self allocation. arXiv preprint arXiv:2005.09610."
categories: [blockchain, security]
---

## Abstract
Propelled by the growth of large-scale blockchain deployments, much recent progress has been made in designing sharding protocols that achieve throughput scaling linearly in the number of nodes. However, existing protocols are not robust to an adversary adaptively corrupting a fixed fraction of nodes. In this paper, we propose Free2Shard -- a new architecture that achieves near-linear scaling while being secure against a fully adaptive adversary.
The focal point of this architecture is a dynamic self-allocation algorithm that lets users allocate themselves to shards in response to adversarial action, without requiring a central or cryptographic proof. This architecture has several attractive features unusual for sharding protocols, including: (a) the ability to handle the regime of large number of shards (relative to the number of nodes); (b) heterogeneous shard demands; (c) requiring only a small minority to follow the self-allocation; (d) asynchronous shard rotation; (e) operation in a purely identity-free proof-of-work setting. The key technical contribution is a deep mathematical connection to the classical work of Blackwell in dynamic game theory.

## Citation
```bibtex
@article{rana2020free2shard,
  title={Free2Shard: Adaptive-adversary-resistant sharding via dynamic self allocation},
  author={Rana, Ranvir and Kannan, Sreeram and Tse, David and Viswanath, Pramod},
  journal={arXiv preprint arXiv:2005.09610},
  year={2020}
}
```