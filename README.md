# SU-Generator
SU_Generator.mlx:
This code generates the generator matrices for special unitary groups. The user specifies the degree and method.
There are two methods that can be employed in this code. One method is to construct the SU generators from subgroups. For example, building SU(5) from SU(3) and SU(2). The other method is to construct the generators by building off of SU(2) by iteratively adding dimensions. These two methods each result in a different basis.

symBreaker.mlx:
This code takes a user-supplied SU(N) group and a specified number of U(1) groups and breaks the symmetry using the Higgs mechanism. It then returns the mass terms of the gauge bosons.

This code contains functions that use the MATLAB® Symbolic Math Toolbox™.
