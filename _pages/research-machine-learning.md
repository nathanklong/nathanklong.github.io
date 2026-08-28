---
title: "Machine Learning"
layout: gridlay
permalink: /research/machine-learning/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/transformer_encoder_seidr_horizontal_pl.svg" alt="Transformer encoder architecture for photonic lantern wavefront estimation" style="width: 100%; height: auto; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Machine Learning
I began working on machine learning when I joined the Trusted Autonomy group at the University of New South Wales, Canberra, under the guidance of Professor Hussein Abbass. My first work on developing neural networks was for the purpose of sea state estimation using the ship-as-a-wave-buoy analogy. I designed simple multi-layer perceptron networks to take uninhabited surface vessel response spectral data to different wave properties as input, then output an estimate of the wave height, frequency, and direction, enabling in-situ, real-time sea state estimation. 

I then worked on *Machine Learning Assisted Continuous-Variable Quantum Communication* for my PhD at the University of New South Wales, Sydney, with a focus on phase estimation for satellite-Earth quantum key distribution. I developed encoder-decoder convolutional neural networks for quantum signal wavefront estimation across turbulent satellite-to-Earth channels using reference pulse intensity distributions as input (phase diversity). I developed long short-term neural networks for relative phase error estimation between quantum signals and reference pulses across turbulent satellite-to-Earth channels. I then developed encoder transformer neural networks for relative wavefront error estimation between quantum signals and reference pulses across turbulent satellite-to-Earth channels using a multi-plane light converter (MPLC) to measure the wavefronts in the Hermite-Gaussian basis. I progressed this work to an experimental campaign at the University of Western Australia, where we transmitted polarisation-multiplexed optical signals across a 2.4 km free-space optical link. We measured the relative wavefront errors between them using an MPLC, then I implemented my transformer architecture to estimate them using the reference pulse MPLC measurements as input.

In my current role as a Postdoctoral Researcher in Astrophotonics and Astronomical Instrumentation at the Sydney Institute for Astronomy, University of Sydney, I am currently developing transformer and convolutional neural network architectures for the purpose of wavefront estimation using photonic lanterns. Photonic lanterns are optical waveguides, which transform point-spread function injected at a multi-mode fibre end to a series of single-mode fibre core outputs. The intensities measured at the output cores are fed into the neural networks, which are then mapped to the pupil-plane wavefront errors. The architectures are therefore designed to learn spatio-temporal transformations.

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

### Figures

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/transformer_encoder_seidr_horizontal_pl.svg"
     alt="tnn-seidr"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Transformer neural network architecture designed for hybrid mode-selective photonic lantern wavefront estimation. Sequence of previous \(M_t\) lantern intensities taken as input, then a wavefront estimate is output for the current time-step \(t\). Transformer layer architecture is depicted in the light blue block, while the attention head architecture is depicted in the yellow block.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/seidr_wf_grid_true_tnn_cnn_kolmogorov_contig_preds.svg"
     alt="tnn-seidr-preds"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Example wavefronts for temporal Von Karman seeing, uncorrected and estimated using a transformer and convolutional neural network.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/ddphi_mn_est_var_bar.svg"
     alt="tnn-mplc"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Transformer neural network relative wavefront error estimation. Correction variance \(\mathrm{Var} (\Delta\tilde{\phi}_{mn,S} − \phi_{mn,S})\) (post-correction, red bars) versus default variance \(\mathrm{Var} (\Delta {\phi}_{mn,R} − \phi_{mn,S})\) (pre-correction, blue bars) for (a) \(N=10\), (b) \(N=30\), and (c) \(N=50\) Hermite-Gaussian mode phase corrections. The purple sections show where the two variances overlap.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/lstm_single_col.svg"
     alt="lstm-phase-estimation"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Long short-term memory unit architecture, developed to estimate a real-time quantum signal phase error \(\Delta\phi_S\) by taking a reference pulse phase error \(\Delta\phi_R\) time-series as input, for LLO-based CV-QKD across satellite-Earth channels.
</figcaption>
</figure>

<!-- <hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;"> -->

