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

This research develops a **scientific machine learning framework** for predicting 3D vehicle collision dynamics by decomposing the response into global rigid-body motion and local structural deformation. Full-scale crash simulations require high computational cost because they must resolve nonlinear contact, plastic deformation, and multi-scale spatio-temporal behavior. By embedding physical decomposition into coordinate-based neural networks, the framework learns continuous collision fields with improved accuracy and physical consistency. This enables faster simulation-based design evaluation when repeated finite element analysis is impractical.

**Reference:**

- **Kim S**, Seo M, Yang S\*, Kang N\* (2026) Rigid-Deformation Decomposition AI Framework for 3D Spatio-Temporal Prediction of Vehicle Collision Dynamics. [_Advanced Engineering Informatics_](https://www.sciencedirect.com/journal/advanced-engineering-informatics), 104749. [https://doi.org/10.1016/j.aei.2026.104749](https://doi.org/10.1016/j.aei.2026.104749)

<div class="research-btn-wrap">
<a href="https://kim-sanghyuk.github.io/vehicle-collision-demo/project" target="_blank" class="research-btn">🔗 Project Page — Live Demo Available</a>
</div>
<p class="research-demo-note">Try the live demo of vehicle collision simulation on the project page.</p>

</div>

<div class="research-section" markdown="1">

## Optimization Algorithm

![2025_NEUCOM_graphical_absract](/images/2025_NEUCOM_graphical_absract.png){: width="100%" height="100%"}

Deep neural network training requires both fast convergence and strong generalization. This research develops a **projected variable three-term conjugate gradient algorithm** that improves the training path of neural networks by reducing convergence to sharp minima while maintaining the stability of higher-order optimization. The method supports more reliable model training across language modeling, image classification, and engineering prediction tasks, providing an optimization strategy for deep learning models used in complex engineering problems.

**Reference:**

- **Kim S**, Kim H\*, Kang N, Lee TH\* (2025) Projected variable three-term conjugate gradient algorithm for enhancing generalization performance in deep neural network training. [_Neurocomputing_](https://www.sciencedirect.com/journal/neurocomputing), 131568. [https://doi.org/10.1016/j.neucom.2025.131568](https://doi.org/10.1016/j.neucom.2025.131568)

- Kim H, Wang C, Byun H, Hu W\*, **Kim S**, Jiao Q, Lee TH\* (2023) Variable three-term conjugate gradient method for training artificial neural networks. [_Neural Networks_](https://www.sciencedirect.com/journal/neural-networks) 159:125–136. [https://doi.org/10.1016/j.neunet.2022.12.001](https://doi.org/10.1016/j.neunet.2022.12.001)

</div>
