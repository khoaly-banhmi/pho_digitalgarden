---
title: 03 2D and 3D motion
description: 
tags:
  - 🌱Seed
  - Physics
  - Spring
date: 2025-02-01
share: true
---
We treat motion in 2D and 3D the same as 1D motion. The 2D and 3D vectors can be reduced to one axis and the [same formula](02 1D Motion) then be applied. 

## Straight Motion

![[Pasted image 20250201133430.png|Pasted image 20250201133430.png]]
A representation of a 2D motion.

![[Pasted image 20250201133826.png|Pasted image 20250201133826.png]]
A 3D representation of a 3D motion.

Displacement: $\vec{r}=x \hat{i}+y \hat{j} + z \hat{k}$. 
$\Delta \vec{r} = \vec{r_{1}}-\vec{r_{2}}$

Average velocity: $\vec{v_{av}} = \frac{\Delta \vec{r}}{\Delta t}$
Instantaneous velocity: $v = \frac{d\vec{r}}{dt}$

$$
\vec{v} = \frac{dx}{dt}\hat{i}+\frac{dy}{dt}\hat{j}+\frac{dz}{dt}\hat{k}
$$
Average acceleration:  $\vec{a_{av}} = \frac{\Delta \vec{v}}{\Delta t}$
Instantaneous acceleration: 
$$
\vec{a}=\frac{d\vec{v}}{dt}=\frac{d^2x}{dt^2}\hat{i}+\frac{d^2y}{dt^2}\hat{j}+\frac{d^2z}{dt^2}\hat{k}
$$
An acceleration vector associated with a velocity vector can be separated into 2 components:
1. $\vec{a}_{\parallel}$: parallel to the velocity vector, increase/decrease the velocity,
2. $\vec{a}_{\perp}$: perpendicular to the velocity vector, curve the path. 
![[Pasted image 20250201135652.png|Pasted image 20250201135652.png]]

## Circular Motion

![[Pasted image 20250201141329.png|Pasted image 20250201141329.png]]

Components:
1. Circular path
2. Center
3. Velocity (tangent to path)
4. Acceleration 
5. Theta angle

For this chapter, we assume that the velocity remains constant. In a circular motion, the acceleration vector is always perpendicular to the velocity vector and point towards the center of the circular path. The two triangles are similar to each other. 

$$
\Delta \vec{v} = \vec{v_{2}}-\vec{v_{1}}
$$
$$
\vec{a_{av}} = \frac{\Delta \vec{v}}{\Delta t}=\frac{{\vec{v_{2}}-\vec{v_{1}}}}{\Delta t}
$$
As the two triangles are similar, $\triangle_{1} \sim \triangle_{2}:$
$$
\frac{\Delta v}{\Delta s}=\frac{v}{R}\implies \Delta v=\frac{v}{R}\Delta s
$$
$$
a_{av}=\frac{{v\Delta s}}{R\Delta t} = \frac{v^2}{R} \text{ because }v=\frac{\Delta s}{\Delta t}
$$
Other formula:
$$
v=\frac{2\pi r}{T}
$$
$$
a_{rad}=\frac{(2\pi R)^2}{T^2R}=\frac{4\pi^2R}{T^2}
$$
