---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Research

<div class="section-card" markdown="1">
### The research program I am building

> **The cytoskeleton is the control system that builds the shape of neural cells. My lab will make that statement quantitative and predictive — and use it to explain why neural form fails to hold in the aging brain.**

How does a neuron acquire and maintain its shape, and why does that capacity decline with age? My work established that neuronal form is not dictated part-by-part but *self-organized*: an excitable actin–actomyosin system, acting across the whole cell, breaks symmetry to specify the axon (*Nature*, 2026). That reframes neuronal morphogenesis as a **dynamical-systems problem** — a cell's shape is the output of a self-organizing dynamical system whose regime is set by definable control parameters, not a fixed blueprint. Over the next six years I will identify those control parameters, show how a cell's mechanical environment sets them, and test whether their drift is a root cause of declining plasticity and repair in the aging nervous system.

What makes this mine to do is a capability chain almost nobody has end-to-end: **biochemical reconstitution → acute control in living neurons and glia → quantitative state inference → sparse validation in tissue.** Few groups span the whole chain, and it is what lets me treat cell shape as an input–state problem rather than a descriptive one: identify a physiological input, measure the state of the force-generating system, perturb the input acutely, and test whether the resulting transition can be predicted and reversed.
</div>

<div class="section-card" markdown="1">
### Three questions, one program

1. **Generate and predict neuronal cytoskeletal states.** Which variables distinguish oscillatory exploration, persistent growth, retraction, and stable polarization — and can a model of them predict what an unseen perturbation will do? I define those state variables from the *Nature* dataset, then test the model with acute perturbations and held-out predictions rather than post-hoc fits. *(The foundation — and the logic that makes everything downstream quantitative.)*
2. **Identify the interface input.** Glia could act on a neuron through soluble factors, contact-dependent cues, the substrate they present, or the forces they transmit. These are usually conflated. I separate them experimentally — conditioned medium, non-contact co-culture, direct contact, defined substrate mechanics — and ask which of them actually moves the neuronal system between states, and by what input–output law. *(The flagship, and the independent territory: mechanics is the leading candidate, not an assumed answer.)*
3. **Stabilize, fail, and reset.** Once a state is selected, what holds it? I test how actin–microtubule organization consolidates the chosen state, and how one ageing, reactive, or disease context shifts the control variable — with the goal of a model-guided reset rather than a description of decline. *(The horizon — where the framework meets ageing, repair, and cortical malformation.)*
</div>

<div class="section-card" markdown="1">
### What will be true by 2032

- A **predictive, parameterized model** of neuronal cytoskeletal self-organization, validated against live imaging — one that says *which* mechanical or molecular perturbation moves a neuron out of the form-permitting regime.
- The **first quantitative demonstration** that a glial mechanical control parameter gates neuronal cytoskeletal organization, and that it drifts with age.
- A mechanistic **entry point for intervention** in age-related loss of structural plasticity — framed as a control parameter to tune, not a molecule to inventory.
</div>

<div class="section-card" markdown="1">
### Approach & toolkit

- **Optogenetic & chemogenetic control of cytoskeletal proteins** — light-induced dimerization and targeted degradation for spatiotemporal control of the cytoskeleton in defined cell types.
- **Primary neuron–glia co-cultures** — to observe how an altered glial cytoskeleton reshapes neighbouring neurons.
- **Sparse conditional perturbation *in vivo*** — AAV / *in utero* electroporation with cortical slice culture, to manipulate cytoskeletal genes in single cells and specific regions while preserving the surrounding tissue.
- **Protein biochemistry & *in-vitro* reconstitution** — isolating native and engineered proteins to link molecular activity to the mechanics and geometry of cytoskeletal networks.
- **Advanced imaging** — live-cell, super-resolution, TIRF, and tissue clearing, with electron-microscopy collaborations for ultrastructure.
</div>

<div class="section-card" markdown="1">
### What I have shown so far

<div class="banner-frame" markdown="0">
<video autoplay loop muted playsinline preload="metadata">
  <source src="{{ site.url }}{{ site.baseurl }}/images/arp3-model.mp4" type="video/mp4">
  Your browser does not support embedded video.
</video>
<div class="banner-caption">A soma-based oscillator selects the axon: Arp2/3-driven actin patches, opposed by actomyosin-mediated global inhibition, drive cycles of neurite retraction until one neurite escapes &mdash; yielding permanent polarization (schematic model).</div>
</div>

<div class="banner-frame" markdown="0">
<video controls loop muted playsinline preload="none" poster="{{ site.url }}{{ site.baseurl }}/images/poster-mechanism.jpg">
  <source src="{{ site.url }}{{ site.baseurl }}/images/arp3-mechanism.mp4" type="video/mp4">
  Your browser does not support embedded video.
</video>
<div class="banner-caption">Zooming in: the subcellular machinery at the soma &mdash; actin patches and protrusions constrained by an actomyosin corset, with localized Arp2/3 and Myosin II activity &mdash; that generates and confines the actin signal driving the oscillator.</div>
</div>

<div class="banner-frame" markdown="0">
<video controls loop muted playsinline preload="none" poster="{{ site.url }}{{ site.baseurl }}/images/poster-tensegrity.jpg">
  <source src="{{ site.url }}{{ site.baseurl }}/images/arp3-tensegrity.mp4" type="video/mp4">
  Your browser does not support embedded video.
</video>
<div class="banner-caption">Inside the neurite (a tensegrity balance of actin and microtubules): with low Arp2/3 activity, actomyosin arcs contract and the neurite retracts; with high Arp2/3 activity, the arcs disassemble and microtubules stabilize and extend the shaft.</div>
</div>

- **A cytoskeletal oscillator for neuronal polarity.** The soma — not the growth cone alone — organizes neuronal polarization: periodic Arp2/3-dependent actin branching remodels a global actomyosin network into an actin wave that biases a single neurite toward axon fate (an Arp2/3–actomyosin local-excitation/global-inhibition system). *First-author paper, published in Nature (2026).*
- **The biochemistry of microtubule nucleation.** I established MOZART1 as an integral part of the γ-tubulin small complex and a driver of its assembly into a nucleation-competent ring, and dissected the mitotic phospho-regulation of γ-TuSC and its receptors.

<div class="banner-frame" markdown="0">
<video controls loop muted playsinline preload="none" poster="{{ site.url }}{{ site.baseurl }}/images/poster-nucleation.jpg">
  <source src="{{ site.url }}{{ site.baseurl }}/images/mt-nucleation.mp4" type="video/mp4">
  Your browser does not support embedded video.
</video>
<div class="banner-caption">How γ-tubulin nucleates a microtubule: the γ-tubulin ring complex (γ-TuRC) caps the minus end and presents a template onto which αβ-tubulin dimers add, growing the lattice toward the plus end (schematic).</div>
</div>

- **Collaborative omics of repair and disease.** Linking pre-synaptic-vesicle gene downregulation to axon-regeneration potential, extracellular-matrix upregulation in reactive astrocytes after stroke, and dorsal-root-ganglion subtype responses to nerve injury.
</div>

<div class="section-card" markdown="1">
### Watch a talk

<div class="banner-frame" markdown="0">
<div class="yt-embed" data-ytid="Kd7ejCS3kHg" role="button" tabindex="0" aria-label="Play the recorded lecture">
<img class="yt-embed__poster" src="{{ site.url }}{{ site.baseurl }}/images/talk-nycu-2022.jpg" alt="Invited lecture at the NYCU College of Life Sciences, with Frank Bradke" loading="lazy">
<span class="yt-embed__play" aria-hidden="true"></span>
</div>
<div class="banner-caption">Invited lecture at the NYCU College of Life Sciences (2022), co-presented with Frank Bradke — on neuronal polarization, the cytoskeleton, and axon growth &amp; regeneration. (Loads from YouTube only when you press play.)</div>
</div>
</div>

<div class="section-card" markdown="1">
### Cover art

Three artistic directions created for the study — the polarizing neuron rendered against the actin-wave oscillator that selects its axon.

<div class="cover-gallery" markdown="0">
<figure><img src="{{ site.url }}{{ site.baseurl }}/images/cover-mono.jpg" alt="Cover artwork: a monochrome neuron over interference waves" loading="lazy"><figcaption>Interference waves</figcaption></figure>
<figure><img src="{{ site.url }}{{ site.baseurl }}/images/cover-inkwash.jpg" alt="Cover artwork: an ink-wash rendering of a polarizing neuron" loading="lazy"><figcaption>Ink wash</figcaption></figure>
<figure><img src="{{ site.url }}{{ site.baseurl }}/images/cover-ocean.jpg" alt="Cover artwork: neurites rendered as cresting ocean waves" loading="lazy"><figcaption>Actin wave</figcaption></figure>
</div>
</div>
