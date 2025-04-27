---
title: 03 Finite Differences
description: Your note description here
tags:
  - 🌱Seed
  - Physics
  - TAMU
date: 2025-03-11
share: true
---
## Learning objectives:

1. Can calculate velocity and acceleration from position measurements in time
2. Can account for the errors in the position measurements

Problem: Engineers usually don't have a perfect function of position over time, if we do, nothing can stop us from conquering the world HAHAHA! Instead we have a a table of position over time, we can **use finite differences to calculate velocity and acceleration.** 

## Finite Differences

1. First Order Forward Finite Difference
$$
f'(x)=\frac{{f(x+\Delta x)-f(x)}}{\Delta x}
$$
2. First Order Backward Finite Difference
$$
f'(x)=\frac{{f(x)-f(x-\Delta x)}}{\Delta x}
$$
3. Second Order Centered Finite Difference
$$
f'(x)=\frac{{f(x+\Delta x)-f(x-\Delta x)}}{2\Delta x}
$$
As the denominator is larger, Second Order Centered Finite Difference is more accurate! Want to dive more? Learn about Taylor Series!

## Treating Data Set

To not make arts in engineering, we should treat the data using moving average:
$$
\bar{x}_{i}=\frac{{x_{i+1}+x_{i}+x_{i-1}}}{3}
$$
To gain more accurate data, you can use multiple moving averages or higher order finite differences. However, note that using them means you will loose data points. 