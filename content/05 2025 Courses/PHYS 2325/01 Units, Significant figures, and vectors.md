---
title: Units, Significant figures, and vectors
description: 
tags:
  - TAMU Spring 2025
  - 🌱Seed
date: 2025-1-16
share: true
---
Unit 1, University Physics
# Units
Use the SI units, including meters (m) for lengths, kilogram (kg) for masses, and second (s) for time

# Significant figures
Usually need 3 to 4 sig figs for correct calculations. Review [[Significant figures and rounding|Significant figures and rounding]]

# Vectors
Vectors have 3 components:
1. Starting point
2. Direction
3. Magnitude (big, small, large?)

## Calculating with vectors
### Adding vectors graphically
There are 2 methods for adding vectors:
1. Head-tail
2. Parallelogram

These methods can be used to determine the direction of the resultant vectors, and the magnitude via physical measuring (you can draw them by scale, and measure the length resultants to determine their magnitude). However, this results in limited accuracy, so another method is developed, components of vectors.

### Vectors subtraction
This part will need to be added later.

### Components of vectors
Vectors can be represented on a x-y plain, then those vectors will have two components (example with vector A):
1. x-component, written as:$$
A_{x} = A\cos(\theta)
$$
2. y-component, written as:$$
A_{y}=A\sin(\theta)
$$
3. Theta: the angle the vectors make with the x+ axis $$
\theta = \tan^{-1}\left( \frac{A_{y}}{A_{x}} \right)
$$
![[Pasted image 20250115141452.png|Pasted image 20250115141452.png]]

Be careful when finding theta. Theta is always measured from x+ axis, counterclockwise. If other angles are given, always find theta before doing calculations.

### Unit vectors
Unit vectors are used to conveniently display vectors components and its magnitude
$$
\vec{A}=A_{x}\hat{i}+A_{y}\hat{j}+ A_{z}\hat{k}
$$
### Scalar product (dot product)
The name is quite explanatory, the result of the product is a number, a magnitude, not a vector. The notation for this product is a dot
$$
\vec{A}\cdot\vec{B}=|\vec{A}||\vec{B}|\cos \theta=A_{x}B_{x}+A_{y}B_{y}+A_{z}B_{z}(unit^2)
$$
There are two ways to calculate scalar product, using magnitudes and theta, or using components of vectors.

### Vector (Cross) product
The result of this product is a vector. There are two components to be determined:
1. Magnitude:$$
|\vec{A}\times\vec{B}|=|\vec{A}||\vec{B}|\sin \phi
$$
2. Direction: Use the Right-hand method:
	1. 4 fingers point towards vector A
	2. Curl to vector B
	3. The direction of the thumb is the direction of the resultant vector