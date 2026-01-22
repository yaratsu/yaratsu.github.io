---
title: "On maximum likelihood estimation of intensity function for Poisson process with deep learning"
date: 2025-10-07

authors:
  - admin
  - Yoshikazu Terada

event: "65th ISI World Statistics Congress"
event_url: "https://www.isi-next.org/conferences/isi-wsc2025/"

location: "World Forum The Hague, The Hague, The Netherlands"

abstract: >
  A Poisson (point) process is a model that describes the random occurrence of events in space-time. Poisson processes have many useful applications because they can model various real-world problems (e.g., the frequency of taxi rides in a given area and the occurrence of earthquakes). The Poisson process can be characterized by an intensity function that describes the average rate of occurrence. Maximum likelihood estimation is often used to estimate the intensity function, and in the case of parametric models, it is known to satisfy nice theoretical properties (e.g., consistency and asymptotic normality) under some regularity conditions. However, for complex real-world problems such as the frequency of taxi rides, it is difficult to prepare a statistical model with a finite-dimensional parameter for the intensity function. In such situations, nonparametric estimation of the intensity function plays a key role. In theoretical studies on nonparametric estimation of intensity functions, many studies have focused on the estimators with explicit expressions. Although the estimators that do not have an explicit representation, such as those using deep learning, show strong performance in practical applications, the theoretical properties of such estimators are not well-studied. This talk focuses on the theoretical analysis of the nonparametric maximum likelihood estimation. Since the Kullback-Leibler (KL) divergence diverges easily in nonparametric estimation, the theoretical analysis for the nonparametric maximum likelihood estimator (NPMLE) is challenging. Therefore, we require strong and unrealistic assumptions for the theoretical analysis of NPMLE via the KL divergence. In real-world applications, though, convergence in the sense of KL divergence is unnecessary and sufficient to show consistency in an appropriate metric. In this study, we apply the simple unified technique to evaluate the Hellinger distance between the NPMLE and the true intensity function and derive the convergence rates of the NPMLE in the Hellinger distance instead of the KL divergence. We can derive the convergence rates under mild and realistic assumptions since the Hellinger distance is bounded whenever the estimated and true intensity functions are bounded. More precisely, We derive the Oracle inequality to evaluate the Hellinger distance between the NPMLE and the true intensity function. Furthermore, as an important application of the Oracle inequality, we derive the convergence rate of NPMLE with deep neural networks.

# 分類用
tags:
  - International Conference

# 発表資料リンク
links: []
---
