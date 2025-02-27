---
layout: post
title:  Improving Neural Network Efficiency With Multifidelity and Dimensionality Reduction Techniques
categories: [publications,multifidelity,neural-networks]
excerpt: Developed projection-enabled multifidelity neural networks to reduce computational costs for a 2D aerodynamic airfoil inverse design problem.
---

Design problems in aerospace engineering often require numerous evaluations of expensive,
non-linear high-fidelity models, resulting in prohibitive computational costs. One way to
address the computational cost is through building surrogates, such as deep neural networks
(DNNs). Specifically, DNNs may be effective when sufficient evaluations of the high-fidelity
model are required such that the up-front training cost is amortized, or in situations that require
real-time responses (such as interactive visualizations). Nevertheless, the data requirements for
adequate training of DNNs are often impractical for engineering applications. To alleviate this
issue, the proposed work utilizes output dimensionality reduction along with information from
multiple models of varying fidelities and cost to develop accurate projection-enabled multifidelity
neural networks (MF-NNs) with a limited computational budget. The dimensionality reduction
leads to a more parsimonious network and the multifidelity aspect adds more training data
from lower-cost, lower-fidelity models. Three approaches for MF-NNs which leverage proper
orthogonal decomposition based projections are introduced: (i) pre-training, (ii) additive, and
(iii) a multi-step method. The MF-NN is applied to approximate the optimal design of 2D
aerodynamic airfoils given the performance and design requirements.

Authors: **Vignesh Sella**, Thomas O’Leary-Roseberry, Xiaosong Du, Mengwu Guo, Joaquim Martins, Omar Ghattas, Karen Willcox, and Anirban Chaudhuri

This work was published at the AIAA SciTech 2025 conference in Orlando, FL. See at the links below, or [here](https://link.growkudos.com/1eypmblwh6o).

<div style="display: flex; justify-content: center; gap: 10px; margin-top: 20px;">
  <a href="https://arc.aiaa.org/doi/10.2514/6.2025-2807" style="background-color: #dda0dd; color: white; padding: 10px; border-radius: 5px; text-decoration: none; font-size: 12px; display: inline-block; width: 50px; text-align: center;">DOI</a>

  <a href="https://www.researchgate.net/publication/387755392_Improving_neural_network_efficiency_with_multifidelity_and_dimensionality_reduction_techniques" style="background-color: #d3d3d3; color: black; padding: 10px; border-radius: 5px; text-decoration: none; font-size: 12px; display: inline-block; width: 50px; text-align: center;">PDF</a>
</div>


