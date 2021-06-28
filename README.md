# Corner-Based-Topology-Optimization-Dataset

General information:
This contains the dataset used for the SAMO journal paper: "Multi-stage deep neural network accelerated topology optimization"

There are sets of inputs and outputs. The inputs represent the boundary conditions of the domain (the same inputs for SILONet). The outputs are the resulting structures from the topology optimization.

The results are separated into 2D and 3D.


INPUTS:
For 2D the naming convention is "inputs_XX.mat", where XX represents the domain density (30 = 0.30). The first column represents the density and columns 2 through 6 are the displacement inputs.

For 3D the naming convention is "inputs_XX_Y.mat", where XX represents the domain density (30 = 0.30) and Y is the index number. The files were split due to filesize constraints.
The first column represents the density and columns 2 through 19 are the displacement inputs.


OUTPUS:
All output files have similar naming conventions as the input files.

2D structures have 3 dimensions. The first dimension is the sample number, the second two dimensions are for the 80X80 structure.

3D structures have 4 dimensions. The first dimension is the sample number, the three other dimensions are for the 20X20X20 structure.
