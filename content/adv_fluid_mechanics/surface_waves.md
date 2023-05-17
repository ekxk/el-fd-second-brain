---
title: Surface Waves
linktitle: Surface Waves
date: '2023-05-17T00:00:00+01:00'

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

# General surface waves problem: 
potential flow, but has different nature of problem and different approach of the solution so that it is separated from the other potential flows.

## boundary conditions
The governing equations are the same, but the unique problem here is that the boundary conditions that needs to be fulfilled.
1. The Laplace Equation
2. Boundary condition in the free surface (y=$eta$) (kinematics) 
3. second boundary condition in the free surface (y=$eta$) (dynamics)
4. boundary condition in the bed (y=-h)

The equations are non-linear, and needs to be imposed on the free surface = difficult.

To simplify this complex problem, we will consider a small amplitude waves (such that the amplitude of the waves is small compared with other lengths such as the wavelength and the liquid depth h.)

# small amplitude plane waves
in addition to small amplitude, we also only consider 2d waves.

the simplifications are somewhat rotating in these concepts:
- non-linear terms --> ~ 0
- Using Taylor expansion, variable at y=$eta$ can be considered at y=0

Some other points:
- Laplace equation now only 2d (x and y)
- F(t) in Bernoulli can be absorbed in to the velocity potential 
- substitute a term from kinematic boundary condition equation into the dynamics one, in order to have the 'preferred form'

Meanwhile, the boundary condition in the bed is the same as it is before.

# Propagation of surface waves
the question we want to answer in this problem is: what is the propagation speed c?

(given amplitude, wavelength, and liquid depth)

how to obtain the answer? solve the flow problem for the velocity potential.


