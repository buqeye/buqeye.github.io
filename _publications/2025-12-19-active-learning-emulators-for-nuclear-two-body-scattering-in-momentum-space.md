---
title: "Active learning emulators for nuclear two-body scattering in momentum space"
author: Abhinav Giri, Jane Kim, Christian Drischler, Charlotte Elster, and Dick Furnstahl
doi: "" 
arxiv: "2512.17842"
pub: ""
link: ""
notebook_link: "https://github.com/buqeye/ms_greedy_emulator"
---

We extend the active learning emulators for two-body scattering in coordinate space with error estimation, recently developed by Maldonado et al. in Phys. Rev. C \textbf{112}, 024002, to coupled-channel scattering in momentum space. Our full-order model (FOM) solver is based on the Lippmann-Schwinger integral equation for the scattering  -matrix as opposed to the radial Schrödinger equation. We use (Petrov-)Galerkin projections and high-fidelity calculations at a few snapshots across the parameter space of the interaction to construct efficient reduced-order models (ROMs), trained by a greedy algorithm for locally optimal snapshot selection. Both the FOM solver and the corresponding ROMs are implemented efficiently in Python using Google's JAX library. We present results for emulating scattering phase shifts in coupled and uncoupled channels and cross sections, and assess the accuracy of the developed ROMs and their computational speed-up factors. We also develop emulator error estimation for both the  -matrix and the total cross section. The software framework for reproducing and extending our results will be made publicly available. Together with our recent advances in developing active-learning emulators for three-body scattering, these emulator frameworks set the stage for full Bayesian calibrations of chiral nuclear interactions and optical models against scattering data with quantified emulator errors. 
