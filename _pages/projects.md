---
layout: archive
title: Projects
permalink: /projects/
author_profile: true
---

## Research Projects

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering**  
  *with Arnab Auddy* · Submitted to the *Journal of Machine Learning Research* (JMLR)  
  [Paper](https://arxiv.org/abs/2607.29675){: .btn--research}
  <details>
      <summary>Abstract</summary>

  <blockquote>
    Existing private methods for estimating density modes mainly recover a single mode, while recovering all modes requires searches from multiple starting locations that can themselves reveal information about individual records. We propose DP-GRAMS, a differentially private algorithm that selects starting locations with a density-aware initialization on a public grid, moves each toward higher estimated density, and groups the endpoints into estimated modes, all within a single privacy budget. We prove that DP-GRAMS satisfies differential privacy and recovers every population mode with high probability, with error bounds that separate statistical error from the cost of privacy and a lower bound showing these rates are nearly optimal. We extend the method to modal regression and clustering and show that it preserves tumor-type separation in cancer gene-expression data.
  </blockquote>

  </details>

- **Matched-Mode Testing: Two-Sample Inference for the Locations of Density Modes**  
  *with Arnab Auddy* · Under review

- **Calibrated Nearest-Neighbor Memorization: Exact Inference and Detectability in Generative Models**  
  *with Abhinav Chakraborty and Arnab Auddy* · In preparation

- **Differentially Private Levenberg–Marquardt**  
  Course project, STAT 8820: Statistical Inference for Dynamical Systems, The Ohio State University (2025)
  <details>
      <summary>Abstract</summary>

  <blockquote>
    Developed a privacy-preserving nonlinear least-squares method by adapting Levenberg–Marquardt updates to satisfy individual-level differential privacy, and evaluated it on nonlinear dynamical-system benchmarks.
  </blockquote>

  </details>
