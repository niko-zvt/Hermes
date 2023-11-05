---
layout: post
title:  A stress-strain instant in your career
date:   2022-05-13 20:00:00
description: At some point in your career, you may be asked to develop a stress-strain law for a new material. If so, it is important to make sure that the stress-strain law satisfies two conditions.
tags: law mechanics thermodynamics mesomechanics solids strength plasticity
comments: true
categories: science
---

#### ⚡️ Continuum mechanics

At some point in your career, you may be asked to develop a stress-strain law for a new material. Maybe this is Hooke's new law? See Fig. 1.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <center>
        {% include figure.html
        path="/assets/img/blog/2022/stress-strain-instant-in-your-career/laws.jpg"
        title="Stress-Strain curves"
        width="50%"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 1. Stress-Strain curves"
        zoomable=true %}
        </center>
    </div>
</div>

If so, it is important to make sure that the stress-strain law satisfies two conditions:

1. It must obey the laws of thermodynamics.
2. It must satisfy the condition of objectivity or indifference to the material structure.

In addition, it is recommended to make sure that the material meets the Drucker stability criterion. Of course, your proposed law will be based on your proposed model (which, perhaps, may not satisfy the conditions in the first approximation), but it should correspond to experimental measurements and, if possible, should be based on some understanding of the physical processes governing the reaction of a [solid](https://en.wikipedia.org/wiki/Solid_mechanics). But only the first two conditions apply to all solids.

[Constitutive models](https://en.wikipedia.org/wiki/Constitutive_equation) describe the material responses to different mechanical and/or thermal loading conditions, which provide the stress-strain relations to formulate the governing equations, together with the conservation laws and kinematic relations.

#### ⚡️ Retrospective

Since Hooke's law represents a straightforward proportional relationship between two variables, its mathematical expressions and implications bear similarities to many other fundamental physical laws. These laws include those governing fluid motion and the polarization of dielectric materials in response to an electric field. Specifically, the tensor equation $$ \sigma = C \varepsilon $$, which connects elastic stresses $$ \sigma $$ to strains $$ \varepsilon $$, shares mathematical similarities with the equation $$ \tau = \mu \dot \varepsilon $$, which relates the viscous stress tensor $$ \tau $$ to the strain rate tensor $$ \dot \varepsilon $$ in the context of viscous fluid flows. It's important to note that while the former concerns static stresses (associated with the extent of deformation), the latter deals with dynamic stresses (associated with the rate of deformation).

#### ⚡️ Thermodynamics
Once I was asked: 

<blockquote>
What does the laws of thermodynamics have to do with it?
</blockquote>

In our favorite continuum mechanics, a material point (or more precisely, a small material particle associated with it with a certain volume $$ dV = O(dx^{3}) $$, where $$ dx \ll L $$) is considered as a thermodynamic system. This is due to the fact that from the point of view of molecular physics, it contains a huge number of molecules. The state of a material point as a thermodynamic system is described by a fairly small and observable set of state parameters, such as: density, internal energy and its components (elastic, thermal, vibrational, etc.), temperature, strain tensor, strain and stress rates, entropy, concentrations of components and phases, magnetization and electric polarization vectors, dislocation density etc.

We are talking about the so-called thermodynamic approach to the construction of defining equations.

#### ⚡️ Physical mesomechanics

There is such an interesting thing, [physical mesomechanics](https://www.springer.com/journal/40334), which considers a loaded solid as a multilevel self-organizing system in which plastic deformation develops self-consistently as a sequential evolution of the loss of shear stability at micro-, meso- and macroscale levels. The carriers of the plastic flow at the meso-level are three-dimensional structural elements (meso-volumes) that move according to the "shift + turn" scheme. Modern mechanics develops along the way of constructing theories and models of deformation of materials, taking into account the evolution of the internal structure.

Physical mesomechanics aims to combine the questions of mechanics of deformable solids in continuum mechanics with the questions of physics of strength and plasticity, which are based on the theory of dislocations.

$$ 
    \begin{array}{@{}c@{}}
    Physical \\
    mesomechanics \\
    \end{array}
    
    \: = \:
    
    \begin{array}{@{}c@{}}
    Mechanics \: of \\
    deformable \: solids \\
    \end{array}

    \: + \:

    \begin{array}{@{}c@{}}
    Physics \: of \: strength \\
    and \: plasticity \\
    \end{array}
$$



The two conditions discussed at the beginning apply to the classical theory of a deformed solids, which extends the mechanics of a material point to the case of a continuous material environment.
