---
title: "Autonomous Vehicle Guidance"
layout: gridlay
permalink: /research/autonomous-vehicle-guidance/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/DT18_Closed_Maneuvers.svg" 
        alt="Closed dynamic soaring maneuvers" 
        style="width: 100%;
            max-width: 550px;
            height: auto;
            display: block;
            margin: 0 auto var(--space-6) auto;
            border-radius: var(--radius);">

## Autonomous Vehicle Guidance

In 2017, I undertook a combined Honours' research project and internship at ISAE-Supaero in Toulouse, France. My project focused on *Regenerative Dynamic Soaring*, where an uninhabited aerial vehicle mimics the flight pattern of Southern Albatrosses (known as Dynamic Soaring) to perpetually glide using wind vectors over the Southern Ocean. Taking this idea one step further, Regenerative Dynamic Soaring uses a windmilling propeller to generate power from the wind vectors, recharging an internal battery.

From 2019 to 2021, I worked as a Naval Architect, where I investigated multi-vessel uninhabited surface vessel (USV) guidance for the purpose of *Sea State Estimation* using the ship-as-a-wave buoy analogy. I modelled the temporal dynamics of the USVs' motion response to different wave inputs, then designed neural networks to map their relationship. I analysed relative trajectories of multiple USVs doing multi-vessel sea state estimation, where wave height, frequency, and direction estimation performance improved with diverse headings, as opposed to common headings.

Further, I worked on *Swarm Shepherding* as a swarm-robotics guidance approach with the Trusted Autonomy group at the University of New South Wales, Canberra. Essentially, shepherding uses the behaviours of sheep agents being herded by a sheep dog (the shepherd). The 'simple' sheep agents are unaware of an objective, their behaviour is emergent. The shepherd understands the objective, manipulating the behaviour of the sheep to achieve the objective via their collective emergent response. Shepherding has several potential applications, ranging from the actual herding of farm animals using autonomous vehicles, to crowd control modelling and simulation.



### Select Papers

{% comment %}
- [Paper title, venue (year)](https://doi.org/10.xxxx/xxxxx)
{% endcomment %}

#### Swarm Shepherding
- [Autonomous Goal-Based Environment Exploration Using Swarm Shepherding and Hilbert Space-Filling Paths (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2021_-_Autonomous Goal-Based Environment Exploration Using Swarm Shepherding and Hilbert Space-Filling Paths.pdf)
- [A Comprehensive Review of Shepherding as a Bio-Inspired Swarm-Robotics Guidance Approach (2020)]({{ site.url }}{{ site.baseurl }}/papers/Long2020_-_A Comprehensive Review of Shepherding as a Bio-Inspired Swarm-Robotics Guidance Approach.pdf)

#### Multi-Vessel Sea State Estimation
- [Multi-Vessel Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2021_MSc_Thesis_-_Multi-vessel sea state estimation using artificial neural networks and vessel response spectral data.pdf)

#### Regenerative Soaring
- [Regenerative Dynamic Soaring Trajectory Augmentation over Flat Terrains (2019)]({{ site.url }}{{ site.baseurl }}/papers/Long2019_-_Regenerative_Dynamic_Soaring_Trajectory_Augmentation_over_Flat_Terrains.pdf)
- [Bio-inspired Regenerative Flight Trajectory Optmisation Over Flat Topography (2018)]({{ site.url }}{{ site.baseurl }}/papers/Long2018_-_Bio-inspired_Regenerative_Flight_Trajectory_Optmisation_Over_Flat_Topography.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography.

### Figures

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/DT18_DS_Open_Maneuvers.svg"
     alt="dyanmic-soaring"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
DT-18 open-loop dynamic soaring trajectory, where an uninhabited aerial vehicle replaces the dynamic soaring pattern flown by the albatrosses. The four dynamic soaring flight phases are high-lighted, with red corresponding to ascent into the wind, yellow to the turn from windward direction to leeward direction, blue to descent with the wind, and purple to the turn from leeward direction to windward direction.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/wave_direction_determination_strategy2.svg"
     alt="multi-vessel"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Wave direction determination strategy schematic. Three vessels are moving with vessel heading angles \(90^\circ\) apart, and three different wave directions shown relative to the vessels.
</figcaption>
</figure>
