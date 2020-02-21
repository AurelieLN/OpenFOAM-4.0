# OpenFOAM-4.0

This code is used in the paper "3D Modeling of crustal polydiapirs with VOF methods". 
We provide solvers and application cases to reproduce our results. 
We use solvers from OpenFOAM-4.0 version : "interFoam" and "multiphaseInterFoam" wich solve bi-fluid and multi-fluid system respectively. They are used to make cases of Van Keken and Weinberg (2-fluid and 3-fluid Rayleigh-Taylor system).
We provide a new solver "interFoamT" based on the bi-fluid solver "interFoam" and the Boussinesq thermal solver "BoussinesqPimpleFoam". It adds a thermal equation with Boussinesq approximation to the solver interFoam, which create a solver that solves a thermal system with 2 fluids. We use it to do ceses of Vatteville and Le Bars (1-fluid and 2-fluid Rayleigh-Bénard system). 
We provide cases presented in the paper : case I of Van Keken benchmark, case II of Weinberg benchmark and case II of Le Bars benchmark. Other cases presented in the paper can be obtained by changing parameters of cases. 
