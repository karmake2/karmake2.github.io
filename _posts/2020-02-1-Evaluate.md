---
title: 'Project Robust IR and NLP Evaluation'
date: 2020-02-01
permalink: /posts/2020/02/Evaluate/
tags:
  - Research
  - Vision
---

We propose the new framework of IR evaluation with both upper and lower bound (UL) normalization of traditional metrics and systematically study the effect of UL-normalization on three popular evaluation metrics. We also propose three different variations of the proposed upper and lower bound (UL) normalized evaluation framework and experiment each of them with three evaluation metrics individually, creating nine new evaluation metrics in total. We show how we can compute more realistic query-specific lower-bounds for evaluation metrics by computing their expected values for each query in case of a randomized ranking of the corresponding documents. We also theoretically prove their correctness.



<center>
  <img src="/images/students/Evaluation.png" alt="Team Evaluation" width="500"/>
</center>
<br>



Overview of Project Robust IR and NLP Evaluation
======
Previous studies have shown that popular Information Retrieval (IR) evaluation metrics, e.g., $nDCG$, $ERR$, $MAP$, are not robust with respect to the variation of the cutoff rank $k$. In this paper, our main goal is to investigate how we can make IR evaluation metrics more robust; more specifically, less sensitive to the variation of cutoff $k$. We start our investigation with the observation that both $nDCG$ and $MAP$ metrics only involve query-specific upper-bound normalization (e.g., normalization with Ideal DCG for $nDCG$ computation); however, none of them include a query-specific lower-bound normalization. For $ERR$, it has neither upper nor lower-bound normalization. We then hypothesize that the high sensitivity of conventional IR evaluation metrics w.r.t. cutoff $k$ is partly due to the fact that none of them include a query-specific lower-bound normalization. To test this hypothesis, we proposed a new general framework for IR evaluation with both upper and lower bound normalization, instantiated the new framework for three popular IR evaluation metrics: $nDCG$, $ERR$, $MAP$ and compared against the corresponding traditional metrics without the proposed normalization. Experimental results show that the proposed upper and lower bound normalized version is indeed more robust (less sensitive) w.r.t. the variation of $k$ for all three metrics studied, decreasing the standard deviation of the original metrics substantially (on average around {68%}) and thus, proving our hypothesis. Hence, we urge the community to use both upper and lower bound normalization while evaluating any IR system from now onward.


<div style='display: flex; justify-content: center;'><img src='https://karmake2.github.io/images/nDCG-robust.png' alt='Image not Loading' style='height:450px;' align='middle'></div><br>



Impact of Project Robust IR and NLP Evaluation
======
Empirical evaluation is a key challenge for any information retrieval (IR) system. The success of an IR system largely depends on the user's satisfaction, thus an accurate evaluation metric is very important for measuring the perceived utility of a retrieval system by the real users. However, previous studies have shown that popular IR evaluation metrics, like $nDCG$, $ERR$, $MAP$, are not robust in terms of accurately capturing the utility perceived by an individual user. For example, in most existing works, $nDCG$ is computed for a user-defined cutoff $k$, i.e., $nDCG@k$, across all queries by taking an average over them. Unfortunately, this practice is problematic for two reasons: 1) Every query is different and the same cut-off $k$ does not accurately capture a user's browsing behavior as well as their perceived utility for all different queries, and 2) Given a particular query, the relative performances of different ranking methods (in terms of $nDCG@k$) vary heavily as we vary $k$ and at the same time, result in high standard deviation (SD) in $nDCG@k$ scores for varying $k$. This clearly suggests the current practice of computing $nDCG@k$ is not robust. In this project, we are working towards addressing these limitations.