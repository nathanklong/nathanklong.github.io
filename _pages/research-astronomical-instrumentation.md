---
title: "Astronomical Instrumentation"
layout: gridlay
permalink: /research/astronomical-instrumentation/
---

<img src="{{ site.url }}{{ site.baseurl }}/images/research/asgard_suite_2.svg" alt="vlti" style="width: 100%; height: auto; border-radius: var(--radius); margin-bottom: var(--space-6);">

## Astronomical Instrumentation

As a Postdoctoral Researcher with the Astralis Instrumentation Consortium at the Sydney Institute for Astronomy, I am leading the design of the Seidr instrument as a part of the Asgard Suite for the Very Large Telescope Interferometer, and contributing to the Photonic Wavefront Imager for the Magellan Clay MagAO-X. 

<hr style="border: 0; border-top: 2px solid #555; margin: 2rem 0;">

*Seidr*

Seidr is a photonic kernel-nulling instrument which will operate within the H-band as a node in Bifrost in the Asgard Instrumentation Suite, at the European Southern Observatory’s Very Large Telescope Interferometer (VLTI). Seidr uses advanced photonic technology to achieve high angular resolution and high contrast imaging of faint companions and circumstellar material.

A kernel-nulling chip destructively suppresses starlight from the VLTI’s four telescopes to reveal faint off-axis signals. Its main science cases include detecting young, self-luminous giant exoplanets, probing warm exozodiacal dust close to nearby stars, and exploring future pathways towards the detection of faint companions such as exomoons.

Seidr introduces hybrid mode-selective photonic lanterns upstream of the kernel nulling chip to optimise light injected into the chip using a mode-selective core. Simultaneously, the lanterns sense wavefront errors on the same optical path using their wavefront sensing cores, reducing non-common-path aberrations and improving nulling performance.

<hr style="border: 0; border-top: 1px dashed #666; margin: 2rem 0;">

*Photonic Wavefront Imager*

Photonic Wavefront Imager (PWI) uses unique Australian-led photonic technology to achieve exquisitely high angular resolution and high-contrast imaging for exoplanet, stellar and active galactic nuclei science.

This project will first build PWI for the Magellan for the MagAO-X extreme adaptive optics system. This will be both a uniquely sensitive science instrument and wavefront sensor, as well as the pathfinder for a subsequent version for the GMT. The GMT PWI will also have the benefit of improving image quality (via mirror-phasing and wavefront sensing) for other GMT instruments.

A version is also being developed for the SCExAO system at the Subaru telescope, and the core technology is currently being integrated into the Asgard suite at ESO’s VLTI. Several PWI instrument instances will therefore come from this project.

<hr style="border: 0; border-top: 2px solid #555; margin: 2rem 0;">


### Select Papers

- [Seidr update: photonic 'black magic' for high-contrast interferometry using kernel-nulling and photonic lanterns (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Seidr update- photonic ‘black magic’ for high-contrast interferometry using kernel-nulling and photonic lanterns.pdf)
- [Overcoming the low signal-to-noise problem for hybrid mode-selective photonic lantern-based wavefront correction using machine learning (2026)]({{ site.url }}{{ site.baseurl }}/papers/Long2026_-_Overcoming the low signal-to-noise problem for hybrid mode-selective photonic lantern-based wavefront correction using machine learning.pdf)

See [Publications]({{ site.url }}{{ site.baseurl }}/publications/) for full bibliography

### Figures

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/kernel_nulling_spie_2.svg"
     alt="seidr-chip"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
Kernel-nulling chip schematic, with four input beams passing through the VLTI and Asgard to Seidr. The nulling stage has one bright output and three dark outputs, the sensing stage produces six asymmetric dark outputs, which are used to construct three kernel observables.
</figcaption>
</figure>

<hr style="border: 0; border-top: 1px dashed #666; margin: 0 0 3rem 0;">

<figure markdown="0"
        style="max-width: 550px; margin: 0 auto 3rem auto;">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/hms-pl6_transfer_matrix_wl=1.55_rms=8.20_ds=0.25_dz=2_rv=1_xyw=320_zlen=50000_tr=20_cut.svg"
     alt="seidr-hmspl"
     style="width: 100%; height: auto; border-radius: var(--radius);">
<figcaption style="font-size: 0.9em; color: var(--text-secondary); margin-top: var(--space-2);">
6-core hybrid mode-selective photonic lantern intensity (left) and phase (right) transfer matrices, representing the transition from the input LP modes to the output single-mode fibre cores. The hybrid mode selectivity can be seen with the ~100% transmission of the LP01 mode to the central core 1.
</figcaption>
</figure>
