---
title: "Free2Shard: Adversary-resistant distributed resource allocation for blockchains"
collection: publications
permalink: /publication/2022-01-free2shard
excerpt: "A novel sharding approach for blockchain systems that provides resilience against adaptive adversaries with information theoretic proofs."
date: 2022-01-01
venue: "Proceedings of the ACM on Measurement and Analysis of Computing Systems"
paperurl: "https://dl.acm.org/doi/10.1145/3508031"
citation: "Rana, R., Kannan, S., Tse, D., & Viswanath, P. (2022). Free2Shard: Adversary-resistant distributed resource allocation for blockchains. Proceedings of the ACM on Measurement and Analysis of Computing Systems, 6(1), 1-31."
categories: [blockchain, security]
---

## Abstract
In this paper, we study a canonical distributed resource allocation problem arising in blockchains. While distributed resource allocation is a well-studied problem in networking, the blockchain setting additionally requires the solution to be resilient to adversarial behavior from a fraction of nodes. Scaling blockchain performance is a basic research topic; a plethora of solutions (under the umbrella of sharding ) have been proposed in recent years. Although the various sharding solutions share a common thread (they cryptographically stitch together multiple parallel chains), architectural differences lead to differing resource allocation problems. In this paper we make three main contributions: (a) we categorize the different sharding proposals under a common architectural framework, allowing for the emergence of a new, uniformly improved, uni-consensus sharding architecture. (b) We formulate and exactly solve a core resource allocation problem in the uni-consensus sharding architecture -- our solution, Free2shard, is adversary-resistant and achieves optimal throughput. The key technical contribution is a mathematical connection to the classical work of Blackwell approachability in dynamic game theory. (c) We implement the sharding architecture atop a full-stack blockchain in 3000 lines of code in Rust -- we achieve a throughput of more than 250,000 transactions per second with 6 shards, a vast improvement over state-of-the-art.

## Citation
```bibtex
@article{rana2022free2shard,
  title={Free2shard: Adversary-resistant distributed resource allocation for blockchains},
  author={Rana, Ranvir and Kannan, Sreeram and Tse, David and Viswanath, Pramod},
  journal={Proceedings of the ACM on Measurement and Analysis of Computing Systems},
  volume={6},
  number={1},
  pages={1--38},
  year={2022},
  publisher={ACM New York, NY, USA}
}
```