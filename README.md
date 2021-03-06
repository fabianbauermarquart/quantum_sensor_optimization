# A Quantum Approach to Optimal Sensor Placement for Self-Driving Cars

Ensuring robust sensor placement is a critical task when it comes to advance autonomous ground vehicle navigation (GVN).
Sensors such as automotive cameras, radar, or lidar are highly complex systems and hence are large cost factors.
While optimizing robust sensor placement promotes save autonomous GVN their use are subjected to certain constraints:

- optimizing the coverage of the vehicle's surrounding
- Some areas require redundant coverage
- Minimizing the costs

Recently, quantum computing has emerged as a great addition to classical computing.
Finding the optimal sensor configuration will be formulated as a multilayered optimization problem.
Therefore quantum computing will be used to provide exponential speedup in comparison to classical computing.

This project aims to find the optimal and cheapest sensor configuration by optimizing the coverage of the region of interest at a minimal cost.
__First__, a set of sensor candidates will be generated.
__Second__, the problem will be mapped to a modification of the exact cover problem.
__Finally__, it will be formulated as an Ising Hamiltonian to use with a variational quantum eigensolver.


## Requirements

- matplotlib
- numpy
- tqdm
- seaborn
- docplex
- qiskit


## Data

The original `Sensor_position` data is copyrighted by BMW group and cannot be made public here.
Intermediate data used for later calculations, however, is included in this repository, with the files `sensor_candidates.csv` and `coverage.csv`.

