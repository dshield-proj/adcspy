# adcspy

## Description of files

* `main.py`  (by running this file, the simulation will be run according to the parameters and plots will be produced)

* `utils.py` (basic functions - mostly for converting between attitude parameterizations. Not much to change here)

* `params.py` (this is the parameter file where simulations can be customized. Everything from the control law gains, desired final attitude, integration step size to the simulation time can be modified in this file.)

* `funcs.py` (this file holds the equations of motion, control law, state estimator, sensor measurements, simulation, and plotting functions. This file only needs to be modified if one plans to change an algorithm or change the plots)

Run the `main.py` file to get simulation results. Any parameters that need to be changed can be found in the `params.py` file. The `funcs.py` file should only need changing if, for example, a different control law or state estimation algorithm is to be implemented. The `utils.py` holds any basic functions that shouldn't need changing.

## References ##
E. Sin, M. Arcak, A. S. Li, V. Ravindra, S. Nag, "Autonomous Attitude Control for Responsive Remote Sensing by Satellite Constellations", AIAA Science and Technology Forum and Exposition (SciTech Forum), Nashville, January 2021 
