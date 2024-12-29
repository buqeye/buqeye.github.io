---
title: "Assessing Correlated Truncation Errors in Modern Nucleon-Nucleon Potentials"
author: Patrick Millican, Dick Furnstahl, Jordan Melendez, Daniel Phillips, and Matt Pratola
doi: "10.1103/PhysRevC.110.044002"
arxiv: "2402.13165"
pub: "Phys. Rev. C 110, 044002"
link: "https://journals.aps.org/prc/abstract/10.1103/PhysRevC.110.044002"
notebook_link: "https://github.com/buqeye/modern_nn_potentials"
---

We test the BUQEYE model of correlated effective field theory (EFT) truncation errors on Reinert, Krebs, and Epelbaum's semi-local momentum-space implementation of the chiral EFT (χEFT) expansion of the nucleon-nucleon (NN) potential. This Bayesian model hypothesizes that dimensionless coefficient functions extracted from the order-by-order corrections to NN observables can be treated as draws from a Gaussian process (GP). We combine a variety of graphical and statistical diagnostics to assess when predicted observables have a χEFT convergence pattern consistent with the hypothesized GP statistical model. Our conclusions are: First, the BUQEYE model is generally applicable to the potential investigated here, which enables statistically principled estimates of the impact of higher EFT orders on observables. Second, parameters defining the extracted coefficients such as the expansion parameter Q must be well chosen for the coefficients to exhibit a regular convergence pattern -- a property we exploit to obtain posterior distributions for such quantities. Third, the assumption of GP stationarity across lab energy and scattering angle is not generally met; this necessitates adjustments in future work. We provide a workflow and interpretive guide for our analysis framework, and show what can be inferred about probability distributions for Q, the EFT breakdown scale Λb, the scale associated with soft physics in the χEFT potential meff, and the GP hyperparameters. All our results can be reproduced using a publicly available Jupyter notebook, which can be straightforwardly modified to analyze other χEFT NN potentials.

