---
title: "Code Review as a Communication Network"
description: "A concise overview of my cumulative, publication-based doctoral thesis on code review as a communication network"
date: "2025-08-21"
showDate: false
showPagination: false
---

This page offers an overview of my cumulative, publication-based doctoral thesis.

## Abstract

**Background:** Modern software systems are often too large and complex for an individual developer to fully oversee, making it difficult to understand the implications of changes. Therefore, most collaborative software projects rely on code review as communication network to foster asynchronous discussions about changes before they are merged. Although prior qualitative studies have revealed that practitioners view code review as a communication network, no formal theory or empirical validation exists. Without formalization and confirmatory evidence, the theory remains uncertain, limiting its credibility, practical relevance, and future development.

**Objective:** In this thesis, our objective is to (1) formalize the theory of code review as a communication network, (2) empirically evaluate the theory across varied perspectives, contexts, and conditions by quantifying the capability of code review to diffuse information among its participants, (3) demonstrate its practical relevance by applying the theory to the domain of tax compliance in collaborative software engineering, and (4) examine how the role of code review as a communication network for collaborative software engineering may evolve in the future.

**Methods:** To formalize the theory of code review as a communication network, we developed and validated a simulation model that operationalizes its core propositions about information diffusion among participants. To empirically evaluate the theory, we employed two complementary research approaches. First, we used the simulation model to conduct *in silico* experiments with closed-source code review systems from Microsoft, Spotify, and Trivago, as well as open-source code review systems from Android, Visual Studio Code, and React, to estimate the upper bound of information diffusion in code review. Second, through an observational study, we quantified the diffusion of information in code review across social, organizational, and architectural boundaries at Spotify. To demonstrate the practical relevance of the theory, we analyzed the code review system of a multinational enterprise as a communication network to reveal the latent collaboration structure among developers across borders, which is taxable. To explore the future of code review as a communication network, we conducted a questionnaire survey with 92 practitioners to gather their expectations and discuss how these anticipated changes may reshape our understanding of code review.

**Results** By formalizing the theory of code review as a communication network modelled as a time-varying hypergraph, we were able to empirically demonstrate that traditional time-agnostic models substantially overestimate information diffusion in code review. Throughout our empirical studies, we found substential evidence supporting the theory of code review as a communication network: We confirmed that code review is capable of diffusing information quickly and widely among participants, even at a large scale. We also observed extensive information diffusion across social, organizational, and architectural boundaries at Spotify corroborating our theory. However, we also found that information diffusion patterns in open-source code review systems differ significantly, suggesting that findings from open-source environments may not directly apply to closed-source contexts. Through applying the theory of code review as a communication network in the domain of tax compliance, we were able to uncover the significant and previously unrecognized tax risks associated with collaborative software engineering within multinational enterprises. While practitioners consider code review also in the future a core practice in collaborative software engineering, we identify a potential risk that generative AI may undermine code review’s role as a human communication network.

**Conclusion:** Our work on understanding code review as a communication network contributes not only to theory-driven, empirical software engineering research but also lays the groundwork for practical applications, particularly in the context of tax compliance. Future research is needed to explore the evolving role of code review as a communication network.

## Fulltext

{{< button href="main.pdf" target="_self" >}}
Download PDF
{{< /button >}}

## Publications

This section details the thesis contributions, with each chapter—aside from the introduction—based on a manuscript submitted to a peer-reviewed venue.

| Chapter | Study | Link |
|---|---|---|
| Chapter&nbsp;2 | Michael Dorner, Darja Šmite, Daniel Mendez, Krzysztof Wnuk, and Jacek Czerwonka. 2022. Only Time Will Tell: Modelling Information Diffusion in Code Review with Time-Varying Hypergraphs. In *ACM / IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM)*, 2022. ACM. 10.1145/3544902.3546254 | <a href="/publications/only-time-will-tell/" target="_blank" rel="noopener">→</a> |
| Chapter&nbsp;3 | Michael Dorner, Daniel Mendez, Krzysztof Wnuk, Ehsan Zabardast, and Jacek Czerwonka. The Upper Bound of Information Diffusion in Code Review. 2025. *Empirical Software Engineering Journal* 30, 1 (2025). 10.1007/s10664-024-10442-y | <a href="/publications/upper-bound-of-information-diffusion-in-code-review/" target="_blank" rel="noopener">→</a> |
| Chapter&nbsp;4 | Michael Dorner and Daniel Mendez. The Capability of Code Review as a Communication Network. Manuscript currently under review at *Journal of Empirical Software Engineering*. | <a href="/publications/capability-of-code-review-as-a-communication-network" target="_blank" rel="noopener">→</a> |
| Chapter&nbsp;5 | Michael Dorner, Daniel Mendez, Ehsan Zabardast, Nicole Valdez, and Marcin Floryan. *Measuring Information Diffusion in Code Review at Spotify*. Registered report accepted at *International Symposium on Empirical Software Engineering and Measurement (ESEM)*; manuscript currently under review at *Journal of Empirical Software Engineering*. | <a href="/publications/measuring-information-diffusion-in-code-review-at-spotify/" target="_blank" rel="noopener">→</a> |
| Chapter&nbsp;6 | Michael Dorner, Maximilian Capraro, Oliver Treidler, Tom-Eric Kunz, Darja Šmite, Ehsan Zabardast, Daniel Mendez, and Krzysztof Wnuk. Taxing Collaborative Software Engineering. 2024. *IEEE Software* 41, 4 (2024), 143--150. 10.1109/MS.2023.3346646 | <a href="/publications/taxing-collaborative-software-engineering/" target="_blank" rel="noopener">→</a> |
| Chapter&nbsp;7 | Michael Dorner, Andreas Bauer, Darja Šmite, Lukas Thode, Daniel Mendez, Ricardo Britto, Stephan Lukasczyk, Ehsan Zabardast, and Michael Kormann. Quo Vadis, Code Review?. Manuscript under review at *IEEE Software*. |  |

## Defense

**When?** September 23, 2025, 14:00

**Where?** J1630 on [Campus Karlskrona](https://www.bth.se/eng/about-bth/this-is-bth/maps-and-premises-2/)

### Opponent

[Felix Dobslaw](https://www.miun.se/en/personnel/d/felixdobslaw/), Mid Sweden University

### Committee

- [Brian Fitzgerald](https://lero.ie/people/brian-fitzgerald), University of Limerick and Lero, Ireland
- [Emma Söderberg](https://portal.research.lu.se/en/persons/emma-söderberg), Lund University, Sweden
- [Burak Turhan](https://turhanb.net), University of Oulu, Finland
