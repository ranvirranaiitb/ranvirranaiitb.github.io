---
title: "Proof of diligence: Cryptoeconomic security for rollups"
collection: publications
permalink: /publication/2024-02-proof-of-diligence
excerpt: "A novel protocol that provides cryptoeconomic security guarantees on computation for blockchain rollups, coprocessors or any compute infrastructure primitive."
date: 2024-02-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2402.07241"
citation: "Sheng, P., Rana, R., Bala, S., Tyagi, H., & Viswanath, P. (2024). Proof of diligence: Cryptoeconomic security for rollups. arXiv preprint arXiv:2402.07241."
categories: [blockchain, security]
---

## Abstract
Layer 1 (L1) blockchains such as Ethereum are secured under an "honest supermajority of stake" assumption for a large pool of validators who verify each and every transaction on it. This high security comes at a scalability cost which not only effects the throughput of the blockchain but also results in high gas fees for executing transactions on chain. The most successful solution for this problem is provided by optimistic rollups, Layer 2 (L2) blockchains that execute transactions outside L1 but post the transaction data on L1.
The security for such L2 chains is argued, informally, under the assumption that a set of nodes will check the transaction data posted on L1 and raise an alarm (a fraud proof) if faulty transactions are detected. However, all current deployments lack a proper incentive mechanism for ensuring that these nodes will do their job ``diligently'', and simply rely on a cursory incentive alignment argument for security.
We solve this problem by introducing an incentivized watchtower network designed to serve as the first line of defense for rollups. Our main contribution is a ``Proof of Diligence'' protocol that requires watchtowers to continuously provide a proof that they have verified L2 assertions and get rewarded for the same. Proof of Diligence protocol includes a carefully-designed incentive mechanism that is provably secure when watchtowers are rational actors, under a mild rational independence assumption.

## Citation
```bibtex
@article{sheng2024proof,
  title={Proof of diligence: Cryptoeconomic security for rollups},
  author={Sheng, Peiyao and Rana, Ranvir and Bala, Senthil and Tyagi, Himanshu and Viswanath, Pramod},
  journal={arXiv preprint arXiv:2402.07241},
  year={2024}
}
```