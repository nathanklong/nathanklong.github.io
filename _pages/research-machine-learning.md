---
title: "Machine Learning"
layout: gridlay
permalink: /research/machine-learning/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/transformer_encoder_seidr_horizontal_pl.svg" alt="Transformer encoder architecture for photonic lantern wavefront estimation" style="width: 100%; height: auto; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Machine Learning
Neural network architectures for temporal and spatial phase estimation —
CNN and transformer models mapping photonic lantern core power measurements to
wavefronts, the training data pipeline, and performance across noise cases.
Expand into several paragraphs.

### Select Papers

{% comment %}
#### Phase Estimation (Photonic Lantern)
{% endcomment %}

#### Phase Estimation (Continuous-Variable Quantum Communication)
- [Relative wavefront error correction over a 2.4-km free-space optical link via machine learning (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Relative wavefront error correction over a 2.4-km free-space optical link via machine learning.pdf)
- [Quantum Wavefront Correction Via Machine Learning for Satellite‐to‐Earth CV‐QKD (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Quantum Wavefront Correction Via Machine Learning for Satellite‐to‐Earth CV‐QKD.pdf)
- [Machine Learning for Phase Estimation in Satellite-to-Earth Quantum Communication (2025)]({{ site.url }}{{ site.baseurl }}/papers/Long2025_-_Machine Learning for Phase Estimation in Satellite-to-Earth Quantum Communication.pdf)
- [Phase Correction using Deep Learning for Satellite-to-Ground CV-QKD (2024)]({{ site.url }}{{ site.baseurl }}/papers/Long2024_-_Phase Correction using Deep Learning for Satellite-to-Ground CV-QKD.pdf)
- [A Survey of Machine Learning Assisted Continuous-Variable Quantum Key Distribution (2023)]({{ site.url }}{{ site.baseurl }}/papers/Long2023_-_A Survey of Machine Learning Assisted Continuous-Variable Quantum Key Distribution.pdf)

#### Sea State Estimation
- [Response Component Analysis for Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2022_-_Response Component Analysis for Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data.pdf)
- [Multi-Vessel Sea State Estimation Using Artificial Neural Networks and Vessel Response Spectral Data (2021)]({{ site.url }}{{ site.baseurl }}/papers/Long2021_MSc_Thesis_-_Multi-vessel sea state estimation using artificial neural networks and vessel response spectral data.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography

<figure markdown="0" style="margin: 0 0 var(--space-6) 0;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/lstm_single_col.svg"
     alt="lstm-phase-estimation"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
LSTM unit architecture, developed to estimate a real-time quantum signal phase error \Delta\phi_S by taking a reference pulse phase error \Delta\phi_R time-series as input.
</figcaption>
</figure>

<figure markdown="0" style="margin: 0 0 var(--space-6) 0;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/transformer_encoder_seidr_horizontal_pl.svg"
     alt="tnn-seidr"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
TNN architecture designed for hybrid mode-selective photonic lantern wavefront estimation. Sequence of previous \M_t lantern intensities taken as input, then a wavefront estimate is output for the current time-step \t. Transformer layer architecture is depicted in the light blue block, while the attention head architecture is depicted in the yellow block.
</figcaption>
</figure>
