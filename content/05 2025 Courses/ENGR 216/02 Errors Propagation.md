---
title: 02 Errors Propagation
description: How to convey errors in measurements when calculating
tags:
  - TAMU
  - Spring
  - 🌱Seed
date: 2025-1-23
share: true
---
## Why propagation?

With the example of measuring the diameter of the plastic donut, we know that there are errors in measurements. We display the measurement like this:
$$
\text{value} = \text{mean} \pm \text{standard error unit}
$$
With the example and measurement of the previous lecture, we know that the value is:
$$
\text{diameter} = 3.02\pm 0.02 in
$$
Now with that measurement, we want to make a box for the donut. We will calculate with that measurement, but how much is the error for the box? That's why we propagate the errors. 

## Errors notation

To write value $x$ with its error, we write $x \pm \delta x$. In these examples, we assume that the errors are all random and uncorrelated. 

## Arbitrary functions of one variable

With one variable to propagate, we calculate the errors using this formula:
$$
\delta q = \bigg|\frac{dq}{dx}\bigg|\delta x
$$
This formula can be applied to any function based on one independent variable like $q=f(x)$.

## Uncertainty in a function of several variables

Let $q=f(x,y,z,...)$, then:
$$
\delta q = \sqrt{ \bigg(\frac{dq}{dx} \delta x\bigg)^2 + \bigg(\frac{dq}{dy} \delta y\bigg)^2 + \bigg(\frac{dq}{dz} \delta z\bigg)^2 + \dots}
$$
You might ask why not adding them up? Because of their porbabilistic nature of errors and their uncorrelation. 
## Partial derivatives

When taking the derivatives of a function with multiple variables, we focus on on variable at a time. The other variable will be treated as constants. For example, taking the derivative of $g(x,y,z)=x^2yz^3+xy^3z^2$:
$$
\frac{dg}{dx}=2xyz^3+y^3z^2
$$
$$
\frac{dg}{dy}=x^2z^3+x3y^2z^2
$$
$$
\frac{dg}{dz}=x^2y3z^2+xy^32z
$$
