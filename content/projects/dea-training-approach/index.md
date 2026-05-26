---
title: "Adaptive Sinkhorn Divergence for Quantum Circuit Born Machines"
authors:
  - kshitij_dea
date: 2026-04-01
summary: |
  Investigating the Sinkhorn Divergence as a cost function for QCBMs and proposing the Dynamic Entropic Annealing training approach to simultaneously improve trainability and accuracy under finite measurement shots.
share: false
image:
  caption: ''
  focal_point: Smart
---

## Overview

A major hurdle in training Quantum Circuit Born Machines (QCBMs) and other variational quantum algorithms is achieving a high accuracy in approximating the target state. This accuracy is heavily affected by various factors, one of the most critical being the choice of the loss function in Quantum Generative Modeling.

As the primary focus of my MS thesis at IISER Bhopal's QuCIS Lab, I studied the behavior of one such cost function: the **Sinkhorn Divergence**. This metric is derived from Optimal Transport theory and acts as an entropy-regularized version of the Wasserstein Distance.

Key aspects of this research include:
- **Entropy Regularization Impact:** Investigated the behavior of entropy regularization on both the trainability and the overall accuracy of the generative model, specifically when the number of measurement shots is finite.
- **Novel Theoretical Findings:** Discovered novel empirical behaviors that challenge the theoretical worst-case bounds traditionally dictated by the Sinkhorn metric.
- **Dynamic Entropic Annealing:** Proposed a novel training approach—*Dynamic Entropic Annealing of the Sinkhorn Divergence*—designed to retain robust trainability while significantly improving the approximation accuracy of the model.
