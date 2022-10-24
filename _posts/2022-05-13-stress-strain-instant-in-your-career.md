---
layout: post
title:  A stress-strain instant in your career
date:   2022-05-13 20:00:00
description: At some point in your career, you may be asked to develop a stress-strain law for a new material. If so, it is important to make sure that the stress-strain law satisfies two conditions.
tags: law mechanics thermodynamics mesomechanics solids strength plasticity
comments: true
categories: science
---

## Continuum mechanics
At some point in your career, you may be asked to develop a stress-strain law for a new material. If so, it is important to make sure that the stress-strain law satisfies two conditions:

<blockquote>
1. It must obey the laws of thermodynamics.
</blockquote>
<blockquote>
2. It must satisfy the condition of objectivity or indifference to the material structure.
</blockquote>

In addition, it is recommended to make sure that the material meets the Drucker stability criterion. Of course, your proposed law will be based on your proposed model (which, perhaps, may not satisfy the conditions in the first approximation), but it should correspond to experimental measurements and, if possible, should be based on some understanding of the physical processes governing the reaction of a [solid](https://en.wikipedia.org/wiki/Solid_mechanics). But only the first two conditions apply to all solids.

[Constitutive models](https://en.wikipedia.org/wiki/Constitutive_equation) describe the material responses to different mechanical and/or thermal loading conditions, which provide the stress-strain relations to formulate the governing equations, together with the conservation laws and kinematic relations.

## Thermodynamics
Once I was asked: 

<blockquote>
What does the laws of thermodynamics have to do with it?
</blockquote>

In our favorite continuum mechanics, a material point (or more precisely, a small material particle associated with it with a certain volume $$ dV = O(dx^{3}) $$, where $$ dx \ll L $$) is considered as a thermodynamic system. This is due to the fact that from the point of view of molecular physics, it contains a huge number of molecules. The state of a material point as a thermodynamic system is described by a fairly small and observable set of state parameters, such as: density, internal energy and its components (elastic, thermal, vibrational, etc.), temperature, strain tensor, strain and stress rates, entropy, concentrations of components and phases, magnetization and electric polarization vectors, dislocation density etc.

We are talking about the so-called thermodynamic approach to the construction of defining equations.

## Physical mesomechanics
#### UPD: 2022-05-14
There is such an interesting thing, [physical mesomechanics](https://www.springer.com/journal/40334), which considers a loaded solid as a multilevel self-organizing system in which plastic deformation develops self-consistently as a sequential evolution of the loss of shear stability at micro-, meso- and macroscale levels. The carriers of the plastic flow at the meso-level are three-dimensional structural elements (meso-volumes) that move according to the "shift + turn" scheme. Modern mechanics develops along the way of constructing theories and models of deformation of materials, taking into account the evolution of the internal structure.

Physical mesomechanics aims to combine the questions of mechanics of deformable solids in continuum mechanics with the questions of physics of strength and plasticity, which are based on the theory of dislocations.

```
Physical mesomechanics = Mechanics of deformable solids + Physics of strength and plasticity
```

The two conditions discussed at the beginning apply to the classical theory of a deformed solids, which extends the mechanics of a material point to the case of a continuous material environment.