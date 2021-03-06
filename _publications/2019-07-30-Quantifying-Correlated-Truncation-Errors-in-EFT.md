---
title:  "Quantifying correlated truncation errors in effective field theory"
author: "Jordan Melendez, Dick Furnstahl, Daniel Phillips, Matt Pratola, and Sarah Wesolowski"
arxiv: "1904.10581"
doi: "10.1103/PhysRevC.100.044001"
pub: "Phys. Rev. C 100, 044001 (2019)"
link: "https://journals.aps.org/prc/abstract/10.1103/PhysRevC.100.044001"
notebook_link: "https://github.com/buqeye/gsum/blob/master/docs/notebooks/correlated_EFT_publication.ipynb"
---

Effective field theories (EFTs) organize the description of complex systems into an infinite sequence of decreasing importance. Predictions are made with a finite number of terms, which induces a truncation error that is often left unquantified. We formalize the notion of EFT convergence and propose a Bayesian truncation error model for predictions that are correlated across the independent variables, e.g., energy or scattering angle. Central to our approach are Gaussian processes that encode both the naturalness and correlation structure of EFT coefficients. Our use of Gaussian processes permits efficient and accurate assessment of credible intervals, allows EFT fits to easily include correlated theory errors, and provides analytic posteriors for physical EFT-related quantities such as the expansion parameter. We demonstrate that model-checking diagnostics---applied to the case of multiple curves---are powerful tools for EFT validation. As an example, we assess a set of nucleon-nucleon scattering observables in chiral EFT. In an effort to be self contained, appendices include thorough derivations of our statistical results. Our methods are packaged in Python code, called gsum, that is available for download on GitHub.
