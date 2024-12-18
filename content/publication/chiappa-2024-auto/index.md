---
title: Auto-bidding in real-time auctions via Oracle Imitation Learning (OIL)
authors:
- Alberto Silvio Chiappa
- Briti Gangopadhyay
- Zhao Wang
- Shingo Takamatsu
date: '2024-12-18'
publishDate: '2024-12-18T08:19:59.421040Z'
publication_types:
- manuscript
publication: preprint

abstract: Online advertising has become one of the most successful business models of the internet era. Impression opportunities are typically allocated through real-time auctions, where advertisers bid to secure advertisement slots. Deciding the best bid for an impression opportunity
    is challenging, due to the stochastic nature of user behavior and the variability of advertisement traffic over time.
    In this work, we propose a framework for training auto-bidding agents in multi-slot second-price auctions to maximize acquisitions (e.g., clicks, conversions) while adhering to budget and cost-per-acquisition (CPA) constraints. We exploit the insight that, after an advertisement campaign concludes, determining the optimal bids for each impression opportunity can be framed as a multiple-choice knapsack problem (MCKP) with a nonlinear objective. We propose an "oracle" algorithm that identifies a near-optimal combination of impression opportunities and advertisement slots, considering both past and future advertisement traffic data.
    This oracle solution serves as a training target for a student network which bids having access only to real-time information, a method we term Oracle Imitation Learning (OIL).
    Through numerical experiments, we demonstrate that OIL achieves superior performance compared to both online and offline reinforcement learning algorithms, offering improved sample efficiency. Notably, OIL shifts the complexity of training auto-bidding agents from crafting sophisticated learning algorithms to solving a nonlinear constrained optimization problem efficiently.

summary: OIL combines operations reserach techniques and imitation learning to train an auto-bidding agent for leal-time auctions.

tags:
- Preprint
- Reinforcement Learning
- Imitation Learning
- Autonomous Agents
  
featured: true

url_pdf: 'https://arxiv.org/pdf/2412.11434'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
- name: arXiv
  url: https://arxiv.org/abs/2412.11434
---
