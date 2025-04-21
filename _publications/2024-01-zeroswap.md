---
title: "ZeroSwap: Data-Driven Optimal Market Making in Decentralized Finance"
collection: publications
permalink: /publication/2024-01-zeroswap
excerpt: "A novel approach to market making in decentralized finance that optimizes trading strategies using data-driven methods."
date: 2024-01-01
venue: "International Conference on Financial Cryptography and Data Security"
paperurl: "https://arxiv.org/abs/2310.09413"
citation: "Nadkarni, V., Hu, J., Rana, R., Jin, C., Kulkarni, S., & Viswanath, P. (2024). ZeroSwap: Data-Driven Optimal Market Making in Decentralized Finance. International Conference on Financial Cryptography and Data Security, 209-227."
categories: [blockchain, defi]
featured: true
---

## Abstract
Automated Market Makers (AMMs) are major centers of matching liquidity supply and demand in Decentralized Finance. Their functioning relies primarily on the presence of liquidity providers (LPs) incentivized to invest their assets into a liquidity pool. However, the prices at which a pooled asset is traded is often more stale than the prices on centralized and more liquid exchanges. This leads to the LPs suffering losses to arbitrage. This problem is addressed by adapting market prices to trader behavior, captured via the classical market microstructure model of Glosten and Milgrom. In this paper, we propose the first optimal Bayesian and the first model-free data-driven algorithm to optimally track the external price of the asset. The notion of optimality that we use enforces a zero-profit condition on the prices of the market maker, hence the name ZeroSwap. This ensures that the market maker balances losses to informed traders with profits from noise traders. The key property of our approach is the ability to estimate the external market price without the need for price oracles or loss oracles. Our theoretical guarantees on the performance of both these algorithms, ensuring the stability and convergence of their price recommendations, are of independent interest in the theory of reinforcement learning. We empirically demonstrate the robustness of our algorithms to changing market conditions.

## Citation
```bibtex
@article{nadkarni2023zeroswap,
  title={ZeroSwap: Data-driven Optimal Market Making in DeFi},
  author={Nadkarni, Viraj and Hu, Jiachen and Rana, Ranvir and Jin, Chi and Kulkarni, Sanjeev and Viswanath, Pramod},
  journal={arXiv preprint arXiv:2310.09413},
  year={2023}
}
```