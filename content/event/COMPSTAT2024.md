---
title: "Nonparametric estimation of conditional class probabilities using deep neural networks"
date: 2024-08-30

authors:
  - admin
  - Yoshikazu Terada

event: "The 26th International Conference on Computational Statistics"
event_url: "http://www.compstat2024.org/"

location: "the University of Giessen, Germany"

abstract: >
  Consider the nonparametric logistic regression problem. In the logistic regression, the maximum likelihood estimator is usually considered, and the excess risk is the expectation of the Kullback-Leibler (KL) divergence between the true and estimated conditional class probabilities. However, in the nonparametric logistic regression, the KL divergence could diverge easily, and thus, the convergence of the excess risk is difficult to prove or does not hold. Several existing studies show the convergence of the KL divergence under strong assumptions. In most cases, the goal is to estimate the true conditional class probabilities. Thus, instead of analyzing the excess risk itself, it suffices to show the consistency of the maximum likelihood estimator in some suitable metric. Using a simple unified approach for analyzing the nonparametric maximum likelihood estimator (NPMLE), the convergence rates of the NPMLE are directly derived in the Hellinger distance under mild assumptions. Although the results are similar to the results in some existing studies, simple and more direct proofs are provided for these results. As an important application, the convergence rates of the NPMLE are derived with deep neural networks, and the derived rate is shown to achieve the minimax optimal rate nearly.

# 分類用
tags:
  - International Conference

# 発表資料リンク
links:
  - name: Slides
    url: "/slides/COMPSTAT2024.pdf"
---
