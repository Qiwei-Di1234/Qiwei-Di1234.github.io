---
permalink: /
title: "Qiwei Di"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

Welcome to my homepage! My name is Qiwei Di. I'm a third-year CS PhD student at UCLA, fortunate to be advised by Prof. Quanquan Gu. Previously, I graduated from the math and applied math department in Tsinghua University.

Research Interests
======
My research interests lie in the field of machine learning, especially learning theory and theory-guided applications. I'm working on\
**Reinforcement Learning:** Markov Decision Process, Dueling Bandits, Complexity Measures\
**Diffusion Models:**  Faster ODE/SDE Solvers, Unified Convergence Analysis, Theory of Optimal Transport\
**LLM:** RLHF, LLM Robustness, Retrieval Augmented Generation (RAG)

Recent News
======
A new paper on unified convergence analysis of ODE solvers:\
[Unified Convergence Analysis for Score-Based Diffusion Models with Deterministic Samplers](https://arxiv.org/abs/2410.14237)
Runjia Li, **Qiwei Di**, Quanquan Gu, Preprint.
* We develop a key technical tool which enables us to bound the time derivative of the total variation (TV) distance between the final states of two ODE processes, through the difference in their drift terms and the divergence. As a direct application, we establish convergence guarantees for the continuous-time reverse ODE in the case of the OU forward process.
* We provide a unified convergence analysis framework for diffusion models with deterministic samplers.
* To demonstrate the generality and effectiveness of our framework, we apply it to two typical diffusion model settings, Variance Preserving (VP) forward process with exponential integrator (EI) numerical scheme, and Variance Exploding (VE) forward process with the DDIM numerical scheme.