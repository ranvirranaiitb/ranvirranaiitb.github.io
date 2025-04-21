---
title: "Resolving blockchain trilemmas"
collection: publications
permalink: /publication/2022-05-resolving-blockchain-trilemmas
excerpt: "PhD dissertation examining fundamental trilemmas in blockchain systems and proposing novel solutions."
date: 2022-05-01
venue: "University of Illinois at Urbana-Champaign"
paperurl: "https://www.ideals.illinois.edu/items/126792"
citation: "Rana, R. (2022). Resolving blockchain trilemmas. University of Illinois at Urbana-Champaign."
categories: [blockchain, security]
featured: true
---

## Abstract
Three ideal properties characterize a blockchain: decentralization, security,
and scalability. Existing blockchain designs satisfy at most two of the three
properties; as examples, consider: Bitcoin is decentralized and secure, but
not scalable; EOS, TRON, and several proof-of-stake blockchains are secure
and scalable, but not decentralized; Conflux and IOTA are decentralized
and scalable, but not secure. Unsuccessful attempts to build scalable, decen-
tralized, and secure blockchains, constituting all three properties, have led
to a folk theorem known as the blockchain protocol trilemma, which states
that a blockchain can achieve only two of the three ideal properties. In this
dissertation, we disprove this trilemma by proposing Trifecta, a blockchain
architecture that achieves all three properties by being: (1) decentralized,
with a limited amount of compute, storage, and communication resources
per node; (2) secure against fully adaptive adversaries with hashing power
up to the honest power of the entire network; and (3) throughput scaling
near linearly with the number of network nodes. We implement Trifecta
as a full-stack blockchain in Rust and demonstrate a total throughput of
250K transactions per second. A key component of the Trifecta architecture
is Free2Shard, a distributed resource allocation algorithm that ensures that
each shard has sufficient honest mining power under an adaptive adversary.
We show the performance of Free2Shard to be near information-theoretically
optimal by connecting to the classical work of Blackwell approachability in
dynamic game theory.
In a separate line of work, a blockchain economics trilemma is posited in the
literature: at most two of the following three economic properties are satisfied
by any blockchain design – self-sufficient, rent-free, and resource-efficient.
We argue that Trifecta with Free2Shard optimizes the rent and resource cost
per transaction and propose Advocate to minimize the legal costs associated
with bootstrapping PoW blockchains. Advocate is a bootstrapping gadget that achieves optimal chain quality even under adversarial mining majority
and can be expended to work on any parallel chain type blockchains. We
demonstrate the robustness of Advocate under a 90% adversarial majority
via a full-stack implementation.



## Citation
```bibtex
@phdthesis{rana2022resolving,
  title={Resolving blockchain trilemmas},
  author={Rana, Ranvir},
  year={2022},
  school={University of Illinois at Urbana-Champaign}
}
```