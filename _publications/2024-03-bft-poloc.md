---
title: "BFT-PoLoc: A Byzantine Fortified Trigonometric Proof of Location Protocol using Internet Delays"
collection: publications
permalink: /publication/2024-03-bft-poloc
excerpt: "A novel protocol for secure geographic location verification in distributed systems. The only protocol at its time to provide spoofing-resistant location."
date: 2024-03-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2403.13230"
citation: "Sheng, P., Sevani, V., Rana, R., Tyagi, H., & Viswanath, P. (2024). BFT-PoLoc: A Byzantine Fortified Trigonometric Proof of Location Protocol using Internet Delays. arXiv preprint arXiv:2403.13230."
categories: [networks, security]
---

## Abstract
Internet platforms depend on accurately determining the geographical locations of online users to deliver targeted services (e.g., advertising). The advent of decentralized platforms (blockchains) emphasizes the importance of geographically distributed nodes, making the validation of locations more crucial. In these decentralized settings, mutually non-trusting participants need to {\em prove} their locations to each other. The incentives for claiming desired location include decentralization properties (validators of a blockchain), explicit rewards for improving coverage (physical infrastructure blockchains) and regulatory compliance -- and entice participants towards prevaricating their true location malicious via VPNs, tampering with internet delays, or compromising other parties (challengers) to misrepresent their location. Traditional delay-based geolocation methods focus on reducing the noise in measurements and are very vulnerable to wilful divergences from prescribed protocol.
In this paper we use Internet delay measurements to securely prove the location of IP addresses while being immune to a large fraction of Byzantine actions. Our core methods are to endow Internet telemetry tools (e.g., ping) with cryptographic primitives (signatures and hash functions) together with Byzantine resistant data inferences subject to Euclidean geometric constraints. We introduce two new networking protocols, robust against Byzantine actions: Proof of Internet Geometry (PoIG) converts delay measurements into precise distance estimates across the Internet; Proof of Location (PoLoc) enables accurate and efficient multilateration of a specific IP address. The key algorithmic innovations are in conducting ``Byzantine fortified trigonometry" (BFT) inferences of data, endowing low rank matrix completion methods with Byzantine resistance.

## Citation
```bibtex
@article{sheng2024bft,
  title={BFT-PoLoc: A Byzantine Fortified Trigonometric Proof of Location Protocol using Internet Delays},
  author={Sheng, Peiyao and Sevani, Vishal and Rana, Ranvir and Tyagi, Himanshu and Viswanath, Pramod},
  journal={arXiv preprint arXiv:2403.13230},
  year={2024}
}
```