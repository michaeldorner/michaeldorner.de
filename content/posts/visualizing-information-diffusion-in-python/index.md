---
title: 'Visualizing Information Diffusion in Python'
date: 2024-10-25
research: ["information diffusion", "code review"]
---



The number of reachable participants indicates how far information can spread, and minimal distance between participants indicate how fast information can spread in code review.

Directly visualizing the actual communication networks from our study isn't feasible due to their large size, so instead, we use a randomly generated network with edges only between nodes nearby (euclidean distance) to not overload the visualization.

This is how the animated visualization looks like:

<video controls>
    <source src="visualizing-information-diffusion.mp4" type="video/mp4">
</video>

Feel free to play around with the notebook using Python, networkx, and matplotlib:

{{< gist michaeldorner c53147e36319b10676d33bc47252ab99 >}}
