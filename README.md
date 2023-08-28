# lammps-conp-modified

The following information is mainly taken from the following repository:
https://github.com/zhenxingwang/lammps-conp/tree/master

# Introduction

Constant potential method is an approach to describe charges on electrode atoms in Molecular Dynamics(MD) simulations of Electric Double-Layer Capacitors(EDLCs). The advantage is to take into account the charge fluctuations on the electrode induced by local density fluctuations in the electrolyte solution. This method was developed by Reed et al.<sup>[1]</sup> and some derivation was corrected by Gingrich and Wilson<sup>[2]</sup> later.

The aim of this project is to implement this method into LAMMPS.

Please cite the following article if using this code.

Z. Wang, Y. Yang, D. L. Olmsted, M. Asta and B. B. Laird, J. Chem. Phys. 141, 184102 (2014). http://dx.doi.org/10.1063/1.4899176
