---
title: Hybrid Thompson-UCB for Risk-Aware Classification of Brain Tumours under Limited
  Data
abstract: Brain tumour classification under limited MRI data is not just an accuracy
  problem. It is a risk-aware task because tumour cases misclassified as healthy may
  lead to false reassurance. This study reframes four-class brain image classification
  (glioma, meningioma, pituitary, and healthy) as a single-step contextual bandit
  problem. We propose a framework based on contextual bandits for cost-sensitive classification
  framework for risk-aware learning. The framework incorporates cost-sensitive learning
  directly into the reward system, enabling the agent to focus on clinically risky
  tumour-to-healthy errors and to reduce them by iteratively improving the classification
  policy. This paper employs hybrid Thompson Sampling with Upper Confidence Bound
  (TS-UCB), $\epsilon$-greedy, and Boltzmann exploration policies for risk-aware classification
  with limited brain-tumour data, and evaluates these policies across three data regimes
  using cross-validation. The hybrid TS-UCB exploration policy achieves the strongest
  safety-performance balance, obtaining the lowest tumour-to-healthy error rate and
  the highest healthy-class precision while maintaining competitive validation and
  test accuracies. The results further demonstrate that reward shaping can tune the
  safety-accuracy trade-off by prioritising clinically risky confusions while remaining
  competitive with, and, in some cases, outperforming traditional deep learning techniques
  under limited data. These results suggest that hybrid TS-UCB is suitable for risk-aware
  brain tumour classification when labelled data are scarce and false negatives must
  be controlled.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: marghalani26a
month: 0
tex_title: Hybrid Thompson-UCB for Risk-Aware Classification of Brain Tumours under
  Limited Data
firstpage: 88
lastpage: 97
page: 88-97
order: 88
cycles: false
bibtex_author: Marghalani, Bashayer Fouad and Herrmann, J. Michael
author:
- given: Bashayer Fouad
  family: Marghalani
- given: J. Michael
  family: Herrmann
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
pdf: https://raw.githubusercontent.com/mlresearch/v348/main/assets/marghalani26a/marghalani26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
