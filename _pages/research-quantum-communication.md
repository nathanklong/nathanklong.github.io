---
title: "Quantum Communication"
layout: gridlay
permalink: /research/quantum-communication/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/wiley_aqt_graphic_2.svg" alt="Quantum satellite-Earth link" style="width: 100%; height: auto; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Quantum Communication

From 2021 to 2025, I worked on *Satellite-Based Continuous-Variable Quantum Communication* at the University of New South Wales, with a focus on using machine learning for phase estimation.

<hr style="border: 0; border-top: 2px solid #555; margin: 2rem 0;">

My work investigates how machine learning (ML) can assist state-of-the-art continuous-variable quantum key distribution (CV-QKD) protocols to advance a global Quantum Internet. Relative wavefront errors between multiplexed classical reference pulses and quantum signals pose a significant challenge to the practical implementation of a satellite-Earth CV-QKD network across turbulent atmospheric channels, potentially leading to the destruction of secure key transfer. ML is proposed as a solution, where ML-based wavefront correction algorithms are designed to mitigate the potentially deleterious effects of relative wavefront errors on CV-QKD, as a result of excess noise affecting the quantum signals. This thesis provides the first analysis of two-dimensional spatial relative wavefront errors. The potential causes of relative wavefront errors are explored, their evolution across satellite-Earth channels is simulated, and their effect on achievable secure key rates is evaluated. ML-based wavefront correction algorithms are designed to facilitate enhanced key rates by encoding the wavefront corrections onto a real local oscillator at the receiver. The analysis of relative wavefront errors presented in this thesis culminates in a series of experimental campaigns involving the transmission of multiplexed stronger reference signals and weaker signals across a 2.4~km free-space optical link, providing the first experimental evidence of relative wavefront errors in the context of CV-QKD. Modified ML-based wavefront correction algorithms are then applied to the experimental data, using phase retrieval, resulting in up to a 2/3 reduction in relative phase error variance. Overall, it is shown that ML algorithms can augment state-of-the-art CV-QKD protocols across turbulent atmospheric channels, thereby progressing the practical feasibility of developing a truly global CV-QKD network.

### Select Papers
- [Relative wavefront error correction over a 2.4-km free-space optical link via machine learning (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Relative wavefront error correction over a 2.4-km free-space optical link via machine learning.pdf)
- [Quantum Wavefront Correction Via Machine Learning for Satellite‐to‐Earth CV‐QKD (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Quantum Wavefront Correction Via Machine Learning for Satellite‐to‐Earth CV‐QKD.pdf)
- [A Survey of Machine Learning Assisted Continuous-Variable Quantum Key Distribution (2023)]({{ site.url }}{{ site.baseurl }}/papers/Long2023_-_A Survey of Machine Learning Assisted Continuous-Variable Quantum Key Distribution.pdf)
- [Machine Learning for Phase Estimation in Satellite-to-Earth Quantum Communication (2025)]({{ site.url }}{{ site.baseurl }}/papers/Long2025_-_Machine Learning for Phase Estimation in Satellite-to-Earth Quantum Communication.pdf)
- [Phase Correction using Deep Learning for Satellite-to-Ground CV-QKD (2024)]({{ site.url }}{{ site.baseurl }}/papers/Long2024_-_Phase Correction using Deep Learning for Satellite-to-Ground CV-QKD.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography

### Figures

<figure markdown="0" style="margin: 0 0 var(--space-6) 0;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/system_diagram_nkl_map.svg"
     alt="fso-experiments"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Experimental setup for preparation and measurement of a reference and signal in free-space optical campaign across a 2.4-km link (shown at the bottom right), where an MPLC is used to measure relative wavefront errors between the reference and signal. HG mode intensity and phase profiles shown at the receiver. AOM is an acousto-optic modulator, Pol is a polarizer, PC is a polarization controller, PD is a photodetector, ZBE is zoom beam expander, MC is the mode cleaner, Tx is the transmitter, Rx is the receiver, Ch is the channel, CCR is the corner cube retroreflector, and BENLOg represents our logarithmic photodetectors.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/quadratures.svg"
     alt="tnn-seidr"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Coherent states encoded in electric field quadratures for (a) GMCS protocol showing the coherent state amplitude \(\alpha\) and phase \(\theta\), (b) DM quadrature PSK protocol, and (c) DM 8PSK protocol. The size of the circles represent the size of the vacuum noise.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/"
     alt="tnn-seidr-preds"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
CV-QKD protocol, where my work focuses on the measurement stage, where homodyne/heterodyne measurements of reference pulses are used to estimate relative phase errors between the reference pulses and quantum signals. Later work expanded to wavefront measurements using a multi-plane light converter, then estimating relative wavefront errors between the reference pulses and quantum signals.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/wfs_lstm_cvqkd_circuit.svg"
     alt="tnn-seidr-preds"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Schematic outlining the preparation and measurement of coherent states with quantum signal phase error \(\Delta\phi_S\) estimation. L is a laser source, BS is a beam splitter, AM is an amplitude modulator, PM is a phase modulator, OA is an optical attenuator, PBC is a polarized beam combiner, PBS is a polarized beam splitter, Het is a heterodyne detector, Hom is a homodyne detector, PS is a phase shifter, DL is a delay line, and NN is the phase estimation neural network.
</figcaption>
</figure>
