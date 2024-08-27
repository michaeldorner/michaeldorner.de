---
title: "The Upper Bound of Information Diffusion in Code Review"
date: 2024-01-03
research: ["simulation", "code review"]
venue: "EMSE"
authors:
    - Michael Dorner
    - Daniel Mendez
    - Krzysztof Wnuk
    - Jacek Czerwonka
showDate: false
---

## Abstract

**Background:** Code review, the discussion around a code change among humans, forms a communication network that enables its participants to exchange and spread information. Although reported by qualitative studies, our understanding of the capability of code review as a communication network is still limited.

**Objective:** In this article, we report on a first step towards understanding and evaluating the capability of code review as a communication network by quantifying how fast and how far information can spread through code review: the upper bound of information diffusion in code review.

**Method:** In an in-silico experiment, we simulate an artificial information diffusion within large (Microsoft), mid-sized (Spotify), and small code review systems (Trivago) modelled as communication networks. We then measure the minimal topological and temporal distances between the participants to quantify how far and how fast information can spread in code review.

**Results:** An average code review participants in the small and mid-sized code review systems can spread information to between 72% and 85% of all code review participants within four weeks independently of network size and tooling; for the large code review systems, we found an absolute boundary of about 11000  reachable participants. On average (median), information can spread between two participants in code review in less than five hops and less than five days.

**Conclusion:** We found evidence that the communication network emerging from code review scales well and spreads information fast and broadly, corroborating the findings of prior qualitative work. The study lays the foundation for understanding and improving code review as a communication network. 

## Download

{{< button href="information-diffusion-boundaries.pdf" target="_self" >}}
Download PDF
{{< /button >}}

## Replication Package

{{< github repo="michaeldorner/information-diffusion-boundaries-in-code-review" >}}

## Meta

- DOI: [10.48550/arXiv.2306.08980](https://doi.org/10.48550/arXiv.2306.08980)
- arxiv: https://arxiv.org/abs/2306.08980
- Publisher: Springer