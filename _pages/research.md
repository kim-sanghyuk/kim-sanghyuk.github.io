---
layout: post
title: "Research"
author: "Sanghyuk Kim"
permalink: /research/
---

## Scientific Machine Learning

![Vehicle Collision Dynamics](/images/20260327_Vehicle.png){: width="100%" height="100%"}

This study presents a **rigid-deformation decomposition AI framework** for 3D spatio-temporal prediction of vehicle collision dynamics. Conventional implicit neural representations struggle to capture high-frequency deformation modes in crash simulations. We address this by decoupling global rigid-body motion from local structural deformation through two scale-specific networks (**RigidNet** and **DeformationNet**), achieving a 29.8% reduction in rigid-body motion error, a 17.2% reduction in total interpolation error, and a 46.6% reduction in angular extrapolation error compared to undecomposed baselines. The framework recovers 92% of the directional correlation and 96% of the spatial deformation localization accuracy relative to an oracle upper bound, enabling physically consistent predictions for nonlinear collision dynamics.

**Reference:**

- **Kim S**, Seo M, Yang S, Kang N (2025) Rigid-Deformation Decomposition AI Framework for 3D Spatio-Temporal Prediction of Vehicle Collision Dynamics. _arXiv preprint_ arXiv:2503.19712. [https://arxiv.org/abs/2503.19712](https://arxiv.org/abs/2503.19712)

<div style="text-align:center; margin:16px 0;">
<a href="https://sanghyuk-kim.me/project" target="_blank" style="display:inline-block; padding:12px 28px; background-color:#0066cc; color:#ffffff; font-size:16px; font-weight:bold; text-decoration:none; border-radius:6px;">🔗 Project Page — Live Demo Available</a>
</div>

> Try the **live demo** of vehicle collision simulation on the project page.

---

## Optimization Algorithm

![2025_NEUCOM_graphical_absract](/images/2025_NEUCOM_graphical_absract.png){: width="100%" height="100%"}

This study introduces the **Projected Variable Three-Term Conjugate Gradient (PVTTCG)** algorithm, designed to overcome the trade-off between fast convergence and strong generalization in deep neural network training.
By stabilizing the optimization path through geometric projection, PVTTCG consistently improves generalization performance across benchmarks and real-world applications such as vehicle crash prediction.

**Reference:**

- **Kim S**, Kim H\*, Kang N, Lee TH\* (2025) Projected variable three-term conjugate gradient algorithm for enhancing generalization performance in deep neural network training. [_Neurocomputing_](https://www.sciencedirect.com/journal/neurocomputing), 131568. [https://doi.org/10.1016/j.neucom.2025.131568](https://doi.org/10.1016/j.neucom.2025.131568)

- Kim H, Wang C, Byun H, Hu W\*, **Kim S**, Jiao Q, Lee TH\* (2023) Variable three-term conjugate gradient method for training artificial neural networks. [_Neural Networks_](https://www.sciencedirect.com/journal/neural-networks) 159:125–136. [https://doi.org/10.1016/j.neunet.2022.12.001](https://doi.org/10.1016/j.neunet.2022.12.001)
