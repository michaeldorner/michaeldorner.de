---
title: "The Capability of Code Review as a Communication Network"
date: 2025-05-01
research: ["code review", "information diffusion", "simulation"]
venue: ["TOSEM"]
authors:
    - Michael Dorner
    - Daniel Mendez
---

## Abstract

**Background:** Code review, a core practice in software engineering, has been widely studied as a collaborative
process, with prior work suggesting it functions as a communication network. However, this theory remains
untested, limiting its practical and theoretical significance.

**Objective:** This study aims to (1) formalize the theory of code review as a communication network explicit
and (2) empirically test its validity by quantifying how widely and how quickly information can spread in
code review.

**Method:** We replicate an in-silico experiment simulating information diffusion—the spread of information
among participants—under best-case conditions across three open-source (Android, Visual Studio Code, React)
and three closed-source code review systems (Microsoft, Spotify, Trivago) each modeled as communication
network. By measuring the number of reachable participants and the minimal topological and temporal
distances, we quantify how widely and how quickly information can spread through code review.

**Results:** We demonstrate that code review can enable both wide and fast information diffusion, even at a large
scale. However, this capacity varies: open-source code review spreads information faster, while closed-source
review reaches more participants.

**Conclusion:** Our findings reinforce and refine the theory, highlighting implications for measuring collaboration, generalizing open-source studies, and the role of AI in shaping future code review.

## Downloads

{{< button href="<https://arxiv.org/abs/2306.08980>" target="_blank" >}}
Download PDF
{{< /button >}}

## Replication Package

{{< github repo="michaeldorner/capability-of-code-review-as-communication-network" >}}

## Meta

- arxiv: <https://arxiv.org/abs/2505.13985>
