---
title: "Barracuda: The power of l-polling in proof of stake blockchains"
collection: publications
permalink: /publication/2020-05-barracuda-thesis
excerpt: "Master's thesis presenting the Barracuda protocol for efficient block propagation in blockchains."
date: 2020-05-01
venue: "University of Illinois at Urbana-Champaign"
paperurl: "https://www.ideals.illinois.edu/items/117093"
citation: "Rana, R. (2020). Barracuda: The power of l-polling in proof of stake blockchains. University of Illinois at Urbana-Champaign."
categories: [blockchain, security, networks]
---

## Abstract
This thesis introduces Barracuda, a novel block propagation protocol for proof-of-stake blockchains that significantly improves network efficiency without compromising security. Traditional block propagation protocols in proof-of-stake systems face challenges with block withholding attacks that can undermine consensus. Barracuda addresses this vulnerability by implementing an ℓ-polling mechanism where validators poll multiple peers to retrieve blocks, drastically reducing the effectiveness of block withholding strategies.

The thesis provides a comprehensive theoretical analysis of Barracuda, demonstrating that the protocol maintains security against powerful adversaries, including those with network control capabilities attempting to execute nothing-at-stake attacks. Through mathematical modeling and simulations, I show that Barracuda achieves near-optimal block propagation throughput while preserving the system's security guarantees.

This work contributes to the scalability of proof-of-stake blockchains by enabling more efficient communication without sacrificing the crucial property of resistance to block withholding attacks.

## Citation
```bibtex
@mastersthesis{rana2020barracuda,
  title={Barracuda: The power of l-polling in proof of stake blockchains},
  author={Rana, Ranvir},
  school={University of Illinois at Urbana-Champaign},
  year={2020}
}
```