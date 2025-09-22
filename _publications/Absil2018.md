---
title: "MIQP-based algorithm for the global solution of economic dispatch problems with valve-point effects"
collection: publications
category: conferences
permalink: /publication/Absil2018
excerpt: 'Joint work with Pierre-Antoine Absil and Benoit Sluysmans'
date: 2018-03-10
venue: 'Power Systems Computation Conference (PSCC)'
slidesurl: ''
paperurl: 'https://NicolasStevens.github.io/files/Absil2018.pdf'
bibtexurl: ''
citation: 'Absil, P. A., Sluysmans, B., and Stevens, N. (2018). MIQP-based algorithm for the global solution of economic dispatch problems with valve-point effects. Power Systems Computation Conference (PSCC), pp. 1-7, IEEE.'
---
Even in a static setting, the economic load dispatch problem (ELDP)-namely the cost-optimal distribution of power among generating units to meet a specific demand subject to system constraints-turns out to be a challenge owing to the consideration of valve-point effects (VPE), which make the cost function nonsmooth and nonconvex. We present a new method, termed Adaptive Piecewise-Quadratic Under-Approximation (APQUA), for the global solution of the ELDP with VPE. Unlike the many existing methods for this problem, APQUA produces at each iteration an upper and a lower bound on the globally optimal cost, and the gap between the two bounds is guaranteed to converge to zero as the iteration number grows. Consequently, APQUA is guaranteed to compute the global optimum of the ELDP within any user-prescribed accuracy. Even though APQUA has to call an MIQP solver on increasingly large surrogate problems in order to achieve this unprecedented optimality guarantee, our experiments indicate that the total computation time remains reasonable even when the prescribed accuracy is very high.
