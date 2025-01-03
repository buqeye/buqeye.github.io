---
title: "Fast emulation of quantum three-body scattering"
author: "Xilin Zhang and Dick Furnstahl"
doi: "10.1103/PhysRevC.105.064004"
arxiv: "2110.04269"
pub: "Phys. Rev. C 105, 064004"
link: "https://journals.aps.org/prc/abstract/10.1103/PhysRevC.105.064004"
notebook_link:
---

We develop a class of emulators for solving quantum three-body scattering problems. They are based on combining the variational method for scattering observables and the recently proposed eigenvector continuation concept. The emulators are first trained by the exact scattering solutions of the governing Hamiltonian at a small number of points in its parameter space, and then employed to make interpolations and extrapolations in that space. Through a schematic nuclear-physics model with finite-range two and three-body interactions, we demonstrate the emulators to be extremely accurate and efficient. The computing time for emulation is on the scale of milliseconds (on a laptop), with relative errors ranging from $10^{-13}$ to $10^{-4}$ depending on the case. The emulators also require little memory. We argue that these emulators can be generalized to even more challenging scattering problems. Furthermore, this general strategy may be applicable for building the same type of emulators in other fields, wherever variational methods can be developed for evaluating physical models.
