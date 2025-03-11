---
title: 05 Confidence Intervals
description: Your note description here
tags:
  - 🌱Seed
  - Physics
  - TAMU
date: 2025-03-11
share: true
---
## Learning Objectives:

1. Use z-tables tp compute a confidence interval on the mean, given the population standard deviation

## Central Limit Theorem

In short, CLT says:
1. If a sample size is large enough, it is normally distributed
2. Criteria to know if a data set is large enough:
	1. If pop normal --> sample is normal
	2. If pop not normal but close --> $N>30$
	3. If pop not normal but not even close --> $N\gg500$
Lots of samples can make prediction on the population. 

When you have a large enough sample:
1. Sampling mean $\mu_{\bar{x}}=\mu$
2. Sampling Standard Deviation $\sigma_{\bar{x}}=\frac{\sigma}{\sqrt{ N }}$
You can then find the mean of the population with a confidence interval

## Confidence Interval

Important formula:
1. $z=\frac{{\bar{x}-\mu_{\bar{x}}}}{\sigma_{\bar{x}}}=\frac{{\bar{x}-\mu}}{\frac{\sigma}{\sqrt{ N }}}$
2. $\bar{x}-z_{\alpha/2}\frac{\sigma}{\sqrt{ N }}<\mu<\bar{x}+z_{\alpha/2}\frac{\sigma}{\sqrt{ N }}$