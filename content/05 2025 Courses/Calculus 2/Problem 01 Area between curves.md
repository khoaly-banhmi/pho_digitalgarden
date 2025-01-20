---
title: Problem 01 Area between curves
description: 
tags:
  - TAMU Spring 2025
  - 🌱Seed
date: 2025-1-17
share: true
---
Find the area of the region described.
The region bounded by 
$$
y=e^x \text{ and } y=e^{-2x} \text{, and } x=\ln(5)
$$
This is not a very difficult problem. The reason why I added this to the list is I confused x = ln(5) with y = ln(5), then I came up with so many possible solutions. First, I will solve the original problem, and then solve my "made up" problem with various ways.

![[problem01.png|problem01.png]]

The are of the region made by the two functions and vertical line x = ln(5) can be calculated with the integration expression:$$
\int_{0}^{\ln(5)} (e^x-e^{-2x})dx
$$
$$
= \left( e^x+\frac{e^{-2x}}{2} \right)\Bigg|^{\ln(5)}_{0}
$$
$$
=\left( 5+\frac{1}{50} \right)-\left( 1+\frac{1}{2} \right)=\frac{88}{25}
$$
very easy huh? Now let's modify the problem into my delulu:
$$
y=e^x \text{ and } y=e^{-2x} \text{, and } y=\ln(5)
$$
![[problem011.png|problem011.png]]

To solve the modified version, there are two methods:
1. 