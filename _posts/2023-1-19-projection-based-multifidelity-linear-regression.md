---
layout: post
title:  Projection-based multifidelity linear regression for data-poor applications
categories: [publications,multifidelity,linear-regression]
excerpt: Developed multifidelity linear regression methods to enhance predictive accuracy in data-poor, high-dimensional applications, showing significant improvement on a hypersonic vehicle surface pressure prediction example.
---

Surrogate modeling for systems with high-dimensional quantities of interest is important for many applications in science and engineering, but remains a challenge in situations where training data are expensive to acquire. This work develops multifidelity (MF) approaches for multivariate multi-output linear regression for data-poor applications with high-dimensional outputs. The MF approach combines information from many low-cost, low-fidelity (LF) model evaluations with limited expensive, high-fidelity (HF) model evaluations. We implement and contrast three MF linear regression methods with projections to a lower-dimensional space through proper orthogonal decomposition basis vectors. The three MF linear regression approaches developed in this work are: (i) an additive method based on the Kennedy-O’Hagan framework, (ii) a direct data augmentation using LF data, and (iii) a data augmentation method using explicit linear regression mapping between LF and HF data. The data augmentation technique combines the HF and the LF data into one training data set and the linear regression model is trained using weighted least squares with different weights for the different fidelity models. We apply the projection-enabled MF linear regression methods to approximate the surface pressure field on a hypersonic vehicle in flight. The MF linear regression outperforms the single-fidelity linear regression in the low data regime of 3 − 10 HF samples with an improvement in the range of approximately 3 − 12% in median accuracy for similar computational cost.

Authors: **Vignesh Sella**, Julie Pham, Anirban Chaudhuri, Karen Willcox

<div style="display: flex; justify-content: center; gap: 10px; margin-top: 20px;">
  <a href="https://doi.org/10.2514/6.2023-0916" style="background-color: #dda0dd; color: white; padding: 10px; border-radius: 5px; text-decoration: none; font-size: 12px; display: inline-block; width: 50px; text-align: center;">DOI</a>

  <a href="https://www.researchgate.net/profile/Anirban-Chaudhuri-4/publication/367312344_Projection-based_multifidelity_linear_regression_for_data-poor_applications/links/63e3d1acdea6121757931091/Projection-based-multifidelity-linear-regression-for-data-poor-applications.pdf" style="background-color: #d3d3d3; color: black; padding: 10px; border-radius: 5px; text-decoration: none; font-size: 12px; display: inline-block; width: 50px; text-align: center;">PDF</a>
</div>


