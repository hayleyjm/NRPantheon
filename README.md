# NRpantheon
Mock Pantheon catalog generated in fully nonlinear general relativity

This repository contains the synthetic distance-redshift data used to constrain H0 as presented in http://arxiv.org/abs/2402.09659. This data was generated from numerical relativity simulations of large-scale structure combined with fully general-relativistic ray tracing calculations. 

Any use of this data in publications or presentations please cite the paper at the above link: Macpherson (2024). 

----

Data description:

Data generated from the 128^3 simulation is in low_res/ and data from the 256^3 simulation is in high_res/. They contain mock catalogs for 50 and 25 observers, respectively. 
Each directory contains a tar file which contains five mock catalogs for each observer.

Each file contains the redshift (z), distance modulus (mu), luminosity distance (dL), and coordinates (HEALPix theta, phi) for each object in each mock catalog. 
See the paper for details. 
