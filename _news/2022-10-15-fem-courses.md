---
layout: post
title: Successfully completed a course at the University of Michigan
date: 2022-10-15 14:00:00-0400
inline: false
publications: true
---

Today I received a certificate confirming the successful completion of the course ["The Finite Element Method for Problems in Physics"](https://www.coursera.org/learn/finite-element-method) of the [University of Michigan](https://umich.edu/).

***

The course was aimed at studying the mathematical techniques underlying the [Finite Element Method](https://en.wikipedia.org/wiki/Finite_element_method). Prof. [Krishna Garikipati](https://www.researchgate.net/profile/Krishna-Garikipati-3) described in great detail the difficulties of formalization of mathematical physics problems in linear and nonlinear formulation. The nuances of constructing finite-dimensional weak form for the multi-dimensional problem, numerical methods of approximation and solving [partial differential equations](https://en.wikipedia.org/wiki/Partial_differential_equation) were considered especially carefully.

The emphasis was on the development of algorithms for solving differential equations and their coding in C++. The basis was an open source FEM library - [deal.II](https://www.dealii.org/), which can later be expanded for other applications.

The course was quite difficult for me, but I was able to successfully complete all practical classes and get a score of 64.5%.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
            {% include figure_redirect.html 
            path="https://s3.amazonaws.com/coursera_assets/meta_images/generated/CERTIFICATE_LANDING_PAGE/CERTIFICATE_LANDING_PAGE~YY74V4KZEZPL/CERTIFICATE_LANDING_PAGE~YY74V4KZEZPL.jpeg"
            title="https://coursera.org/share/7126e9f564641c09a022a042409fcc11"
            url="https://coursera.org/share/7126e9f564641c09a022a042409fcc11"
            class="img-fluid rounded z-depth-1"
            caption-small="Course certificate" %}
    </div>
</div>

Here is a short list of topics that aroused my greatest interest:
<ul>
    <li>Derivation of the weak form using a variational principle;</li>
    <li>The strong and weak forms of steady state heat conduction and mass diffusion;</li>
    <li>Lagrange basis functions in 1 through 3 dimensions;</li>
    <li>Analysis of the integration algorithms for first order, parabolic equations;</li>
    <li>Modal decomposition.</li>
</ul>

Also I hope that there are further materials on shell elements, nonlinear analysis (geometric nonlinearity, plasticity and hyperelasticity).

***

Finite Element Analysis (FEA) is a good choice for problem analysis in complex domains when the area changes (such as during a solid-state reaction with a moving boundary), when the desired accuracy changes over the entire area, or when the solution is not smooth.

There are many good books on FEM/FEA:
<ul>
    <li>{% cite Hughes_FEM %}</li>
    <li>{% cite Zienkiewicz_FEM %}</li>
    <li>{% cite Fish_FEM %}</li>
</ul>
