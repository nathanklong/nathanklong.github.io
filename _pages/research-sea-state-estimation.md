---
title: "Sea State Estimation"
layout: gridlay
permalink: /research/sea-state-estimation/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/coordinate_systems3.svg" alt="Boat-as-a-wavebuoy coordinate systems" style="max-width: 550px; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Sea State Estimation

I worked as a Naval Architect between 2019 and 2021, where I focused on the problem of in-situ, real-time sea state estimation. A solution was to use a ship-as-a-wave buoy, where I designed neural networks to build a relationship between the motion response of a vessel and different sea state conditions.

<hr style="border: 0; border-top: 2px solid #555; margin: 2rem 0;">

The use of the `ship as a wave buoy analogy' (SAWB) provides a novel means to estimate sea states, where relationships are established between causal wave properties and vessel motion response information. This study focuses on a model-free machine learning approach to SAWB-based sea state estimation (SSE), using neural networks (NNs) to map vessel response spectral data to statistical wave properties for a small uninhabited surface vessel.

Results showed a strong correlation between heave responses and significant wave height estimates, whilst the accuracy of mean wave period and wave heading predictions were observed to improve considerably when data from multiple vessel degrees of freedom (DOFs) was utilized. Overall, 3-DOF (heave, pitch and roll) NNs for SSE were shown to perform well when compared to existing SSE approaches that use similar simulation setups. One advantage of using small vessels for SAWB was shown as SSE accuracy was reasonable even when motion responses were low (in high-frequency, low wave height sea states).

The SSE approach was subsequently extended to multiple vessels, investigating whether differences in vessel trajectories could improve estimation performance. Multi-vessel configurations reduced SSE error relative to a single vessel, with strategies employing varied or random vessel headings generally outperforming vessels travelling with a common heading. The greatest improvements were observed for mean wave period and wave direction, indicating that trajectory diversity provides complementary vessel response information that can improve the robustness of SAWB-based SSE.

Given the information-dense statistical representation of vessel motion responses in spectral form, as well as the ability of NNs to effectively model complex relationships between variables, the designed SSE method shows promise for future adaptation to mobile, multi-vessel SSE systems using the SAWB approach.

### Select Papers

- [Response Component Analysis for Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2022_-_Response Component Analysis for Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data.pdf)
- [Multi-Vessel Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2021_MSc_Thesis_-_Multi-vessel sea state estimation using artificial neural networks and vessel response spectral data.pdf)
- [Multi-vessel Sea State Estimation Utilising Swarm Shepherding (2019)]({{ site.url }}{{ site.baseurl }}/papers/Long2019_-_Multi-vessel Sea State Estimation Utilising Swarm Shepherding.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography.



### Figures

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/SSE_taxonomy_figure.svg"
     alt="sse-taxonomy"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Taxonomy of ship-as-a-wave-buoy sea state estimation (SSE) methods.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/coordinate_systems3.svg"
     alt="wave-coords"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
The three coordinate systems used to evaluate wave direction: wave-relative, north-east-down, and body-fixed.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/Hs_component_residuals_polar_fix_u.png"
     alt="height-est"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Residual wave height estimation plots polar plots for wave height estimations \(\mathrm{H_s}\) with a fixed USV speed \(\mathrm{U_\pi}\) of 2.5 m/s and varying USV headings \(\mathrm{\mu_{h}}\).
</figcaption>
</figure>
