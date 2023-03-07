# Generate Special Unitary Matrices and Break Symmetry using the Higgs Mechanism

# Files
*SU_Generator.mlx*:
This code generates the generator matrices for special unitary groups. The user specifies the order and method.
There are two methods that can be employed in this code. One method is to construct the SU generators from subgroups. For example, building SU(5) from SU(3) and SU(2). The other method is to construct the generators by building off of SU(2) by iteratively adding dimensions. These two methods each result in a different basis. The output of this code also includes the generators of the lower orders.

*structureconstants.mlx*:
This code returns the structure constants and symmetry coefficients of an SU(N) group.

*symBreaker.mlx*:
This code takes a user-supplied SU(N) group and a specified number of U(1) groups and breaks the symmetry using the Higgs mechanism. It then returns the mass terms of the gauge bosons.

*SO_Generator.mlx*:
This code generates the generator matrices for the special orthogonal groups SO(N). The user specifies the order and whether or not the signs between generators alternate.

*makeQuaternions.mlx*:
This code generates unit quaternions in terms of the Dirac matrices.

*quaternionProduct.mlx*:
This code computes the direct product of two quaternions. This also gives the dot product and cross product between the 3D components of the vectors.

This code contains functions that use the MATLAB® Symbolic Math Toolbox™.
The file *Example.mlx* is provided as a guide of use.

# Purpose
The primary purpose of this code is to assist academics working in quantum field theory. Generating these matrices and associated constants and coefficients can be a tedious task if done by hand. This code does the tedious parts for you.

Matthew E Chasco

Mathworks
