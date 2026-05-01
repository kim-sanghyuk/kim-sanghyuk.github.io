---
layout: post
title: "Research"
author: "Sanghyuk Kim"
permalink: /research/
---

<div class="research-section" markdown="1">

## Scientific Machine Learning

<div style="position:relative; padding-bottom:56.25%; height:0; overflow:hidden; max-width:100%; margin-bottom:1rem; border-radius:4px;">
  <iframe src="https://player.vimeo.com/video/1188288123"
    style="position:absolute; top:0; left:0; width:100%; height:100%; border:0;"
    allow="autoplay; fullscreen; picture-in-picture" allowfullscreen
    title="Vehicle Collision Dynamics Demo"></iframe>
</div>

This study presents a **rigid-deformation decomposition AI framework** for 3D spatio-temporal prediction of vehicle collision dynamics. Conventional implicit neural representations struggle to capture high-frequency deformation modes in crash simulations. We address this by decoupling global rigid-body motion from local structural deformation through two scale-specific networks (_**RigidNet**_ and _**DeformationNet**_), achieving a 29.8% reduction in rigid-body motion error, a 17.2% reduction in total interpolation error, and a 46.6% reduction in angular extrapolation error compared to undecomposed baselines. The framework recovers 92% of the directional correlation and 96% of the spatial deformation localization accuracy relative to an oracle upper bound, enabling physically consistent predictions for nonlinear collision dynamics.

**Reference:**

- **Kim S**, Seo M, Yang S\*, Kang N\* (2026) Rigid-Deformation Decomposition AI Framework for 3D Spatio-Temporal Prediction of Vehicle Collision Dynamics. [_Advanced Engineering Informatics_](https://www.sciencedirect.com/journal/advanced-engineering-informatics), 104749. [https://doi.org/10.1016/j.aei.2026.104749](https://doi.org/10.1016/j.aei.2026.104749)

<div class="research-btn-wrap">
<a href="https://sanghyuk-kim.me/project" target="_blank" class="research-btn">🔗 Project Page — Live Demo Available</a>
</div>
<p class="research-demo-note">Try the live demo of vehicle collision simulation on the project page.</p>

</div>

<div class="research-section" markdown="1">

## Optimization Algorithm

![2025_NEUCOM_graphical_absract](/images/2025_NEUCOM_graphical_absract.png){: width="100%" height="100%"}

This study introduces the **Projected Variable Three-Term Conjugate Gradient (PVTTCG)** algorithm, designed to overcome the trade-off between fast convergence and strong generalization in deep neural network training.
By stabilizing the optimization path through geometric projection, PVTTCG consistently improves generalization performance across benchmarks and real-world applications such as vehicle crash prediction.

**Reference:**

- **Kim S**, Kim H\*, Kang N, Lee TH\* (2025) Projected variable three-term conjugate gradient algorithm for enhancing generalization performance in deep neural network training. [_Neurocomputing_](https://www.sciencedirect.com/journal/neurocomputing), 131568. [https://doi.org/10.1016/j.neucom.2025.131568](https://doi.org/10.1016/j.neucom.2025.131568)

- Kim H, Wang C, Byun H, Hu W\*, **Kim S**, Jiao Q, Lee TH\* (2023) Variable three-term conjugate gradient method for training artificial neural networks. [_Neural Networks_](https://www.sciencedirect.com/journal/neural-networks) 159:125–136. [https://doi.org/10.1016/j.neunet.2022.12.001](https://doi.org/10.1016/j.neunet.2022.12.001)

</div>
