---
title: "Barracuda: the power of ℓ-polling in proof-of-stake blockchains"
collection: publications
permalink: /publication/2019-07-barracuda
excerpt: "A novel P2P protocol for blockchains that improves propagation delay and network security."
date: 2019-07-01
venue: "Proceedings of the twentieth ACM international symposium on Mobile ad hoc networking and computing"
paperurl: "https://dl.acm.org/doi/abs/10.1145/3323679.3326533"
citation: "Fanti, G., Jiao, J., Makkuva, A., Oh, S., Rana, R., & Viswanath, P. (2019). Barracuda: the power of ℓ-polling in proof-of-stake blockchains. In Proceedings of the twentieth ACM international symposium on Mobile ad hoc networking and computing (pp. 71-80)."
categories: [blockchain, security, networks]
featured: true
---

## Abstract
A blockchain is a database of sequential events that is maintained by a distributed group of nodes. A key consensus problem in blockchains is that of determining the next block (data element) in the sequence. Many blockchains address this by electing a new node to propose each new block. The new block is (typically) appended to the tip of the proposer's local blockchain, and subsequently broadcast to the rest of the network. Without network delay (or adversarial behavior), this procedure would give a perfect chain, since each proposer would have the same view of the blockchain. A major challenge in practice is forking. Due to network delays, a proposer may not yet have the most recent block, and may therefore create a side chain that branches from the middle of the main chain. Forking reduces throughput, since only one a single main chain can survive, and all other blocks are discarded. We propose a new P2P protocol for blockchains called Barracuda, in which each proposer, prior to proposing a block, polls ℓ other nodes for their local blocktree information. Under a stochastic network model, we prove that this lightweight primitive improves throughput as if the entire network were a factor of ℓ faster. We provide guidelines on how to implement Barracuda in practice, guaranteeing robustness against several real-world factors.

## Citation
```bibtex
@inproceedings{10.1145/3323679.3326533,
author = {Fanti, Giulia and Jiao, Jiantao and Makkuva, Ashok and Oh, Sewoong and Rana, Ranvir and Viswanath, Pramod},
title = {Barracuda: The Power of ℓ-polling in Proof-of-Stake Blockchains},
year = {2019},
isbn = {9781450367646},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3323679.3326533},
doi = {10.1145/3323679.3326533},
abstract = {A blockchain is a database of sequential events that is maintained by a distributed group of nodes. A key consensus problem in blockchains is that of determining the next block (data element) in the sequence. Many blockchains address this by electing a new node to propose each new block. The new block is (typically) appended to the tip of the proposer's local blockchain, and subsequently broadcast to the rest of the network. Without network delay (or adversarial behavior), this procedure would give a perfect chain, since each proposer would have the same view of the blockchain. A major challenge in practice is forking. Due to network delays, a proposer may not yet have the most recent block, and may therefore create a side chain that branches from the middle of the main chain. Forking reduces throughput, since only one a single main chain can survive, and all other blocks are discarded. We propose a new P2P protocol for blockchains called Barracuda, in which each proposer, prior to proposing a block, polls ℓ other nodes for their local blocktree information. Under a stochastic network model, we prove that this lightweight primitive improves throughput as if the entire network were a factor of ℓ faster. We provide guidelines on how to implement Barracuda in practice, guaranteeing robustness against several real-world factors.},
booktitle = {Proceedings of the Twentieth ACM International Symposium on Mobile Ad Hoc Networking and Computing},
pages = {351–360},
numpages = {10},
keywords = {Stochastic networks, blockchains},
location = {Catania, Italy},
series = {Mobihoc '19}
}


```