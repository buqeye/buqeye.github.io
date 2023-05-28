---
title: "Wave function-based emulation for nucleon-nucleon scattering in momentum space"
author: Alberto Garcia, Christian Drischler, Dick Furnstahl, Jordan Melendez, and Xilin Zhang
doi: "10.1103/PhysRevC.107.054001"
arxiv: "2301.05093"
pub: "Phys. Rev. C 107, 054001"
link: "https://journals.aps.org/prc/abstract/10.1103/PhysRevC.107.054001"
notebook_link: "https://github.com/buqeye/scattering-emulators"
---

Emulators for low-energy nuclear physics can provide fast & accurate predictions of bound-state and scattering observables for applications that require repeated calculations with different parameters, such as Bayesian uncertainty quantification. In this paper, we extend a scattering emulator based on the Kohn variational principle (KVP) to momentum space (including coupled channels) with arbitrary boundary conditions, which enable the mitigation of spurious singularities known as Kohn anomalies. We test it on a modern chiral nucleon-nucleon (NN) interaction, including emulation of the coupled channels. We provide comparisons between a Lippmann-Schwinger equation emulator and our KVP momentum-space emulator for a representative set of neutron-proton (np) scattering observables, and also introduce a quasi-spline-based approach for the KVP-based emulator. Our findings show that while there are some trade-offs between accuracy and speed, all three emulators perform well. Self-contained Jupyter notebooks that generate the results and figures in this paper are publicly available.
