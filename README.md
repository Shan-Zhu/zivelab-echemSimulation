# ZiveLab EchemSimulation

This repo contains excel files to simulate electrochemical experiments on single charge transfer reaction.
* Reaction: A + ne <-> B
* Experiments: Cyclic Voltammetry, Chronoamperometry, Electrochemical Impedance Spectroscopy

![Screenshot](/docs/media/Example_CV.png)

### References

This is based on Prof. M. Rudolph’s early publications, on the Fast Implicit Finite Difference (FIFD) method. D. Britz's book  and A. J. Bard and L. R. Faulkner's textbook were also referred to.
* M. Rudolph, A fast implicit finite difference algorithm for the digital simulation of electrochemical processes, J. Electroanal. Chem., 314 (1991) 13.
* M. Rudolph in I. Rubinstein (Ed.), Physical Chemistry: Principles, Methods and Applications Marcel Dekker, New York, 1995.
* D. Britz, Digital Simulation in Electrochemistry, Lect. Notes Phys. 666 (Springer, Berlin Heidelberg 2005), DOI 10.1007/b97996.
* A. J. Bard, L. R. Faulkner, Electrochemical Methods: Fundamentals and Applications, 2nd. Ed. (John Wiley, New York 2001)

### SIM4U

The FIFD algorithm used here has been applied to [SIM4U](http://zivelab.com). It is aiming to simulate reliable current responses of cyclic voltammetry. You can study how concentrations of species would vary with applied potential changes. In addition, you can see the surface concentration changes as a function of potentials; and further you can investigate with any user-defined mechanism with an arbitrary number of charge transfer steps and first or second-order chemical steps.

The followings are allowed in the SIM4U.
* Single or multiple charge transfer steps and first and second-order chemical steps can be used.
* Cyclic voltammetry method is used for simulation.
* 1D simulation of semi-infinite diffusion processes is used.
* The pre-equilibrium can be applied before simulation.
* The effect of uncompensated resistance and double layer capacitance can be simulated.

The SIM4U is released in free of charge with an ad banner and not included in this repo.
