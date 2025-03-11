# IDR---Isotonic-distributional-regression
This repo contains the material I used and produced to present the paper "Isotonic distributional regression" at the seminar "Conformal and probabilistic predictions" at ETH (supervised by professor Ziegel).

Isotonic distributional regression (IDR) is a powerful non-parametric technique for the estimation of conditional distributions under order restrictions. In a nutshell, IDR learns conditional distributions that are calibrated, and simultaneously optimal relative to comprehensive classes of relevant loss functions, subject to isotonicity constraints
in terms of a partial order on the covariate space. 

For prediction, it is proposed an interpolation method that generalizes extant specifications under the pool adjacent violators algorithm. It is
recommended the use of IDR as a generic benchmark technique in probabilistic forecast problems, as it does not involve any parameter tuning nor implementation choices, except for the selection of a partial order on the covariate space. The method can be combined with subsample aggregation, with the benefits of smoother regression functions and gains in computational efficiency.
