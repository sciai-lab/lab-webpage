---
title: Projects
nav:
  order: 2
  tooltip: Our projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include section.html %}

## Current focus: Orbital-free density functional theory

**What is the kinetic energy of a given ground state electron density? While we know the question holds a significant answer, irritatingly, we do not know how to find it.**

{%
  include figure.html
  image="images/density_slice.webp"
  width="400px"
  caption="Slice through the density difference to the ground state of a molecule."
%}

When predicting the properties of a molecule, it is possible to simplify by separating nuclear and electronic degrees of freedom. The latter are the subject of Electronic Structure Theory, which invokes quantum mechanics to describe the interacting electrons in terms of their many-body wave function $\psi(x_1, ..., x_N)$. For sizeable molecules, this is too expensive and instead Kohn-Sham density functional theory (DFT) is evoked. The latter models the same system merely via one-body functions $\phi_1 (x_1)$, ..., $\phi_N (x_N)$ describing non-interacting electrons moving in an effective potential created by the others. Importantly, these functions lead in principle to the exact electron density $\rho_\mathrm{exact}$, however, approximations for the unknown exchange-correlation energy functionals need to be made. Although highly successful in practice, Kohn-Sham DFT remains a sort of band-aid solution. Why? 


In the 1960s, Hohenberg and Kohn made a tantalizing discovery: for systems in their electronic ground state, knowledge of the electron density alone suffices to compute the exact electronic ground state energy, and wave functions or “orbitals” are not needed! To find the ground state electron density, one minimizes its overall energy in the potential created by atomic nuclei. The overall energy has, of course, a kinetic contribution stemming from the kinetic energy density functional $E_\mathrm{kin} = T[\rho_\mathrm{exact}]$. Vexingly, it has so far been impossible to identify the functional $T[\rho]$ yielding the exact kinetic energy of a given ground state electron density.

Being able to do so is not only of great theoretical interest: it paves the way for variationally optimizing the electronic ground state density without taking recourse to the much more complicated many-body wave functions. This sixty-year old promise, called pure or, more contemporarily, orbital-free DFT, promises computing molecular properties with a complexity growing merely linearly with system size.

The entire team is now focused on developing machine learning methods to *learn* the elusive functional. If successful, this will dramatically speed up the prediction of molecular properties, paving the way to address previously inaccessible questions in the molecular and life sciences. 

{% include list.html data="citations" component="citation" filters="title: KineticNet: Deep learning a transferable kinetic energy functional for orbital-free density functional theory" style="rich" %}


{% include section.html %}

## Selected contributions 

{% include list.html component="card" data="projects" filters="group: " style="small" %}
