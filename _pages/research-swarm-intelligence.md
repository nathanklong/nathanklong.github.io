---
title: "Swarm Intelligence"
layout: gridlay
permalink: /research/swarm-intelligence/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/The_Great_Wave_of_Shepherding.jpg" alt="Swarm shepherding" style="width: 100%; height: auto; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Swarm Intelligence
From 2019 to 2021, I worked on swarm shepherding as a bio-inspired swarm robotics guidance approach, as a member of the Trusted Autonomy group at the University of New South Wales, Canberra.

<hr style="border: 0; border-top: 2px solid #555; margin: 2rem 0;">

The simultaneous control of multiple coordinated robotic agents represents an elaborate problem. If solved, however, the interaction between the agents can lead to solutions to sophisticated problems. The concept of swarming, inspired by nature, can be described as the emergence of complex system-level behaviors from the interactions of relatively elementary agents. Due to the effectiveness of solutions found in nature, bio-inspired swarming-based control techniques are receiving a lot of attention in robotics. One method, known as swarm shepherding, is founded on the sheep herding behavior exhibited by sheepdogs, where a swarm of relatively simple agents are governed by a shepherd (or shepherds) which is responsible for high-level guidance and planning. Many studies have been conducted on shepherding as a control technique, ranging from the replication of sheep herding via simulation, to the control of uninhabited vehicles and robots for a variety of applications.

### Select Papers

- [Autonomous Goal-Based Environment Exploration Using Swarm Shepherding and Hilbert Space-Filling Paths (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2021_-_Autonomous Goal-Based Environment Exploration Using Swarm Shepherding and Hilbert Space-Filling Paths.pdf)
- [A Comprehensive Review of Shepherding as a Bio-Inspired Swarm-Robotics Guidance Approach (2020)]({{ site.url }}{{ site.baseurl }}/papers/Long2020_-_A Comprehensive Review of Shepherding as a Bio-Inspired Swarm-Robotics Guidance Approach.pdf)
- [Multi-vessel Sea State Estimation Utilising Swarm Shepherding (2019)]({{ site.url }}{{ site.baseurl }}/papers/Long2019_-_Multi-vessel Sea State Estimation Utilising Swarm Shepherding.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography.

### Figures

<figure markdown="0"
        style="max-width: 650px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/Research_Links_Figure_4.svg"
     alt="shepherd-taxonomy"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Shepherding mind map. The inner circle is used to categorize the literature as simulation, robotics and artificial intelligence, or a combination of them. Each of these categories is then decomposed into associate sub-categories. A hierarchical tree of shepherding taxonomy is then presented outside the circle, initially split into shepherding guidance or implementation.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/Strombom_Illustration.svg"
     alt="wave-coords"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Schematic outlining shepherding heuristic, where the circles represents radii of influence, and arrows represent vectors. (a) The shepherd approaches the driving position. (b) The shepherd repels a sheep, which is also attracted to its centre of mass. (c) The sheep repels another sheep, which is also attracted to their centre of mass, while the shepherd moves to the new driving position. (d) The shepherd repels two sheep, which are also both attracted to their centre of mass.
</figcaption>
</figure>
