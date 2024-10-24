---
title: "Only Time Will Tell: Modelling Information Diffusion in Code Review with Time-Varying Hypergraphs"
date: 2022-09-20
research: ["simulation", "code review", "information diffusion"]
venue : "ESEM"
authors:
    - Michael Dorner
    - Darja Šmite
    - Daniel Mendez
    - Krzysztof Wnuk
    - Jacek Czerwonka
---

{{< alert "award">}}
**Best Paper Award at ESEM'22**
{{< /alert >}}

## Abstract

**Background:** Modern code review is expected to facilitate knowledge sharing: All relevant information, the collective expertise, and meta-information around the code change and its context become evident, transparent, and explicit in the corresponding code review discussion. The discussion participants can leverage this information in the following code reviews; the information diffuses through the communication network that emerges from code review. Traditional time-aggregated graphs fall short in rendering information diffusion as those models ignore the temporal order of the information exchange: Information can only be passed on if it is available in the first place.

**Aim:** This manuscript presents a novel model based on time-varying hypergraphs for rendering information diffusion that overcomes the inherent limitations of traditional, time-aggregated graph-based models.

**Method:** In an in-silico experiment, we simulate an information diffusion within the internal code review at Microsoft and show the empirical impact of time on a key characteristic of information diffusion: the number of reachable participants.

**Results:** Time-aggregation significantly overestimates the paths of information diffusion available in communication networks and, thus, is neither precise nor accurate for modelling and measuring the spread of information within communication networks that emerge from code review.

**Conclusion:** Our model overcomes the inherent limitations of traditional, static or time-aggregated, graph-based communication models and sheds the first light on information diffusion through code review. We believe that our model can serve as a foundation for understanding, measuring, managing, and improving knowledge sharing in code review in particular and information diffusion in software engineering in general.

## Download

{{< button href="only-time-will-tell.pdf" target="_self" >}}
Download PDF
{{< /button >}}

## Replication Package

{{< github repo="michaeldorner/only-time-will-tell" >}}

## Meta

- DOI: [10.1145/3544902.3546254](https://doi.org/10.1145/3544902.3546254)
- arxiv: https://arxiv.org/abs/2110.07291
- Publisher: https://dl.acm.org/doi/abs/10.1145/3544902.3546254
