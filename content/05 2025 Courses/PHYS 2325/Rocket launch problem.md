---
title: Rocket launch problem
description: How far can a rocket go?
tags:
  - 🌱Seed
  - Spring
  - Physics
date: 2025-01-25
share: true
---
A rocket, initially at rest on the ground, accelerates straight upward from rest with constant (net) acceleration $44.1\text{m/s}^2$ . The acceleration period lasts for time $9.00s$ until the fuel is exhausted. After that, the rocket is in free fall. 

Find the maximum height $y_{max}$ reached by the rocket. Ignore air resistance and assume a constant free-fall acceleration equal to $9.80\text{m/s}^2$ . 

Given: 
* Net acceleration $a_{0}=44.1\text{m/s}^2$ 
* Acceleration lasts for $t=9.00s$
* Free-fall acceleration $g=9.80\text{m/s}^2$

Find: The maximum height reached by the rocket.

Theory:
* $x=x_{0}+v_{0}t+\frac{1}{2}a_{x}t^2$
* $x-x_{0}=\frac{1}{2}(v_{0x}+v_{x})t$
* $v_{x}^2=v_{0x}^2+2a_{x}(x-x_{0})$

Assumption:
* The rocket accelerates upwards with the same acceleration of $a_{0}=44.1\text{m/s}^2$ until the fuel runs out.
* After the fuel runs out, the rocket still ascends upwards but with $g=9.80\text{m/s}^2$ downwards.

Graph: ![[Pasted image 20250125194938.png|Pasted image 20250125194938.png]]

Solution:

The first part: The rocket ascends until the fuel runs out
* $x_{0}=0\text{ m}$
* $v_{0}=0\text{ m/s}$
* $a=44.1\text{ m/s}^2$
* $t=9.00s$

The height the rocket reaches before the fuel runs out
$$
x=x_{0}+v_{0}t+\frac{1}{2}at^2
$$
$$
x=0+(0)9.00+\frac{1}{2}(44.1)(9^2)
$$
$$
x=1.79\times 10^3\text{ m}
$$
When the fuel runs out, the rocket has the velocity of:
$$
x-x_{0}=\frac{1}{2}(v_{0}+v)t
$$
$$
1.79\times 10^3-0=\frac{1}{2}(0+v_{x})(9)
$$
$$
v_{x}=396.9\text{ m/s}
$$
The rocket keeps ascending until the velocity is zero and start free falling:
$$
v_{x}^2=v_{0}^2+2g_{}(x-x_{0})
$$
$$
0=(396.9^2)+2(-9.80)(\Delta x)
$$
$$
\Delta x=8.04\times 10^3\text{ m}
$$
Then the total height the rocket reaches is $9.83\times 10^3\text{ m}$