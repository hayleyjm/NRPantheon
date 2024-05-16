# NRpantheon
Mock Pantheon catalog generated in fully nonlinear general relativity

This repository contains the synthetic distance-redshift data used to constrain H0 as presented in http://arxiv.org/abs/2402.09659. This data was generated from numerical relativity simulations of large-scale structure combined with fully general-relativistic ray tracing calculations. 

Any use of this data in publications or presentations please cite the paper at the above link: Macpherson (2024). 

----

Data description:

Data generated from the three simulations are in the respective directories here. For example, N256_L1024/ contains data from the N=256^3 resolution simulation with physical box length L=1024 Mpc/h (the fiducial case). 
The data from the two lower-resolution simulations used in the Appendix are in the N128_L512/ and N128_L1536/ directories. 
Each directory contains mock catalogs for a set of either 25 or 50 observers, each with 5 random rotations of coordinate directions.

Each file contains the redshift (z), distance modulus (mu), luminosity distance (dL) in Mpc/h, and coordinates (HEALPix theta, phi) for each object in each mock catalog. 
See the paper for details. 
