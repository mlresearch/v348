---
title: Denoising Diffusion Probabilistic Models for Source Camera Identification in
  Image Forensics
abstract: Source Camera Identification (SCI) is a forensic task to determine the physical
  imaging device for a given digital image or video. The problem has raised concern
  with the proliferation of digital cameras in consumer devices, the ease with image
  capturing, editing, and sharing at scale across social media and messaging platforms,
  and the operational need to attribute illicit content in important evidence cases
  like child abuse to specific recording devices in criminal investigations. The main
  signal for SCI is Photo-Response Non-Uniformity (PRNU), classically extracted via
  a denoising filter such as the Wiener filter, which degrades substantially on small
  image patches. We propose a combined framework in which a per-camera Denoising Diffusion
  Probabilistic Model (DDPM) acts as a camera-dependent residual extractor, replacing
  the classical filter, and Linear Discriminant Analysis (LDA) exploits the full NCC
  score vector across all candidate cameras for the final identification decision.
  Evaluated on three benchmarks at $128\times128$ patches, our method achieves macro-averaged
  balanced accuracies of 93.74%, 93.84%, and 92.50% on the Northumbria, Dresden, and
  VISION datasets respectively, outperforming the Wiener filter on all three benchmarks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: farzadpour26a
month: 0
tex_title: Denoising Diffusion Probabilistic Models for Source Camera Identification
  in Image Forensics
firstpage: 68
lastpage: 77
page: 68-77
order: 68
cycles: false
bibtex_author: Farzadpour, Zahra and Ahmed, Farah Nafees and Khelifi, Fouad
author:
- given: Zahra
  family: Farzadpour
- given: Farah Nafees
  family: Ahmed
- given: Fouad
  family: Khelifi
date: 2026-09-30
address:
container-title: Proceedings of the Fourth UK AI Conference 2026
volume: '348'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 9
  - 30
pdf: https://raw.githubusercontent.com/mlresearch/v348/main/assets/farzadpour26a/farzadpour26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
