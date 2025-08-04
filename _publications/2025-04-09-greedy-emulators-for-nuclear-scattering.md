---
title: "Greedy Emulators for Nuclear Two-Body Scattering" 
author: Joshua Maldonado, Christian Drischler, Dick Furnstahl, and Petar Mlinarić
doi: "https://doi.org/10.1103/k77q-f82l" 
arxiv: "2504.06092"
pub: "Phys. Rev. C 112, 024002"
link: "https://journals.aps.org/prc/abstract/10.1103/k77q-f82l"
notebook_link: "https://github.com/buqeye/cs_greedy_emulator"
---

Applications of reduced basis method emulators are increasing in low-energy nuclear physics because they enable fast and accurate sampling of high-fidelity calculations, enabling robust uncertainty quantification. In this paper, we develop, implement, and test two model-driven emulators based on (Petrov-)Galerkin projection using the prototypical test case of two-body scattering with the Minnesota potential and a more realistic local chiral potential. The high-fidelity scattering equations are solved with the matrix Numerov method, a reformulation of the popular Numerov recurrence relation for solving special second-order differential equations as a linear system of coupled equations. A novel error estimator based on reduced-space residuals is applied to an active learning approach (a greedy algorithm) to choosing training samples ("snapshots") for the emulator and contrasted with a proper orthogonal decomposition (POD) approach. Both approaches allow for computationally efficient offline-online decompositions, but the greedy approach requires much fewer snapshot calculations. These developments set the groundwork for emulating scattering observables based on chiral nucleon-nucleon and three-nucleon interactions and optical models, where computational speed-ups are necessary for Bayesian uncertainty quantification. Our emulators and error estimators are widely applicable to linear systems. 
