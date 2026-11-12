<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img src="assets/hero-light.svg" alt="TeRToNi — student at Letovo School, interested in neural operators, scientific machine learning and physics. A wireframe surface illustrates multiscale structure." width="100%">
</picture>

## About

I am a student at Letovo School interested in how mathematics and computation can help us understand physical systems. My focus is on scientific machine learning: in particular, learning operators between function spaces and studying how their behavior changes across scales and spatial discretizations.

I work with Python and Java, and I am drawn to questions where a useful model must be understood as well as computed.

<br>

## Research projects

### 01 — WFNO / Coupled

**Fourier–wavelet neural operators · ongoing research**

This project explores how Fourier-based and wavelet-based representations might interact within a neural operator. Fourier representations provide a way to describe global structure, while wavelets offer localized representations at multiple scales. The question is how information exchange between coarse-scale features and fine details might support the learning of operators on functions.

The directions of inquiry include accuracy, numerical stability under varying conditions, and generalization across spatial discretizations, including cross-resolution transfer. These are research questions, not claims of established results.

![Conceptual diagram: an input field branches into Fourier and wavelet representations, whose features exchange information before producing a learned operator output.](assets/wfno-diagram.svg)

<sub>Figure 01. Conceptual illustration; it is neither an exact implementation diagram nor an experimental result.</sub>

<br>

### 02 — PDE Lab

**Partial differential equations · visualization and model comparison**

PDE Lab is a research-oriented application for visualizing solutions to partial differential equations and comparing prediction errors across computational models. It is designed around a practical question: what can the structure of a numerical prediction—and of its error—tell us about a model's behavior?

![Three illustrative fields: a reference solution, a model prediction, and their signed difference.](assets/pde-lab.svg)

<sub>Figure 02. Schematic fields, not measurements. The first two panels share a color scale; the signed residual uses a separate scale.</sub>

<br>

## Open science mission

![Open science: knowledge grows when its foundations remain open to examination.](assets/open-science.svg)

> I want the work I contribute to make its reasoning visible enough for others to test, question, and carry forward.

Science is cumulative: a result becomes a foundation when others can understand the assumptions and methods beneath it. Openness, to me, is therefore more than releasing code. It is a way to invite independent examination and make scientific reproducibility possible. That aspiration has practical limits and requires care; it is not a claim that every project is already open or reproducible.

Mathematics gives an investigation structure; computation lets us explore its consequences. When the reasoning and tools can be inspected and reused, a question can grow beyond the person who first asked it. I hope to contribute to that shared process, where criticism and extension are part of discovery.

<br>

## Research interests

**Learning operators**  ·  Neural operators  /  Scientific machine learning  /  Numerical generalization

**Understanding physical systems**  ·  Physics  /  Partial differential equations  /  Numerical stability

**Working across scales**  ·  Multiscale methods  /  Fourier and wavelet representations  /  Cross-resolution transfer

<br>

*Mathematics frames the question; computation explores it; shared inquiry deepens understanding.*
