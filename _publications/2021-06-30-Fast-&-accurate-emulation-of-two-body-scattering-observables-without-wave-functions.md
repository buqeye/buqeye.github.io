---
title:  "Fast & accurate emulation of two-body scattering observables without wave functions"
author: "Jordan Melendez, Christian Drischler, Alberto Garcia, Dick Furnstahl, and Xilin Zhang"
doi: "10.1016/j.physletb.2021.136608"
arxiv: "2106.15608"
pub: "Phys. Lett. B 821, 136608 (2021)"
link: "https://www.sciencedirect.com/science/article/pii/S0370269321005487?via%3Dihub"
notebook_link:
---

We combine Newton's variational method with ideas from eigenvector continuation to construct a fast & accurate emulator for two-body scattering observables. The emulator will facilitate the application of rigorous statistical methods for interactions that depend smoothly on a set of free parameters. Our approach begins with a trial $K$ or $T$ matrix constructed from a small number of exact solutions to the Lippmann--Schwinger equation. Subsequent emulation only requires operations on small matrices. We provide several applications to short-range potentials with and without the Coulomb interaction and partial-wave coupling. It is shown that the emulator can accurately extrapolate far from the support of the training data. When used to emulate the neutron-proton cross section with a modern chiral interaction as a function of 26 free parameters, it reproduces the exact calculation with negligible error and provides an over 300x improvement in CPU time.  
