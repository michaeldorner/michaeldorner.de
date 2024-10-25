---
title: "Visualizing Information Diffusion in Python"
description: ""
summary: ""
date: 2024-10-25
research: ["information diffusion", "code review"]
---

For [my journal-first presentation at ESEM 2024](https://conf.researchr.org/details/esem-2024/esem-2024-journal-first/5/The-upper-bound-of-information-diffusion-in-code-review) on our work on [the upper bound of information diffusion in code review]({{<ref "/publications/upper-bound-of-information-diffusion-in-code-review/index.md" >}}), I prepared a visualization to make the idea of our simulation easier understandible. In fact, the idea of our simulation is quite simple: We model communication networks that emerge from code reviews, with participants represented as vertices and code reviews as edges connecting these vertices. To simulate how information spreads, we trace the shortest paths between participants involved in code reviews.

The number of reachable participants indicates how far information can spread, and minimal distance between participants indicate how fast information can spread in code review.

Directly visualizing the actual communication networks from our study isn't feasible due to their large size, so instead, we use a randomly generated network with edges only between nodes nearby (euclidean distance) to not overload the visualization.

This is how the animated visualization looks like:

<video controls>
    <source src="visualizing-information-diffusion.mp4" type="video/mp4">
</video>

Feel free to play around with the notebook using Python, networkx, and matplotlib:

{{< gist michaeldorner c53147e36319b10676d33bc47252ab99 >}}
