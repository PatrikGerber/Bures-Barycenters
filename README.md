# Averaging on the Bures-Wasserstein manifold: dimension-free convergence of gradient descent
In this repository you find all the code necessary to reproduce the figures in our paper "Averaging on the Bures-Wasserstein manifold: dimension-free convergence of gradient descent", published at NeurIPS 2021. 
### Authors
-  [Jason M. Altschuler](https://www.mit.edu/~jasonalt/)
- [Sinho Chewi ](https://chewisinho.github.io/)
- [Patrik Gerber](https://patrikgerber.github.io/)
- [Austin J. Stromme](http://www.mit.edu/~astromme/)

### Structure of the repo
Everything is written in Julia (version 1.5.1 at the time of writing) notebooks. There are 6 notebooks, with contents as follows:
1. Data_generation.ipynb : Contains functions for data generation. See Sections 3.3, 4.3, 5.3 and Appendix F for further details. 
2. Barycenter_algorithms.ipynb: Contains functions relating to Euclidean and Riemannian methods for computing BW barycenters (GD, EGD, SGD, ESGD and SDP + helper functions)
3. Barycenters.ipynb: Reproduces Figures 1,2,3,7,8
4. Median.ipynb: Reproduces Figures 5,6
5. Regularized barycenter.ipynb: Reproduces Figure 4
6. RFW.ipynb: Reproduces Figure 7