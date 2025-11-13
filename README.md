For simulating the irradiation response of an alloy system, we used the EAM potential which was smoothly 
joined to the Ziegler–Biersack–Littmark (ZBL) potential for small interatomic separations. 

Details for the ZBL-implementation can be found in the *ZBL.cpp files which should be placed 
into the src folder of your LAMMPS installation path together with the *ZBL.h files, before compilation.

Also included is an example LAMMPS input file for performing the PKA simulations and the file to be loaded
for defining electron stopping.The potential file is the one used in https://doi.org/10.1038/s41467-019-11464-7.

Reference: 
Zhen Zhang, Zhengxiong Su, Bozhao Zhang, Qin Yu, Jun Ding, Tan Shi, Chenyang Lu, Robert O. Ritchie, and Evan Ma. 
Effect of local chemical order on the irradiation-induced defect evolution in CrCoNi medium-entropy alloy. 
Proc. Natl. Acad. Sci. U.S.A. 120, e2218673120 (2023).
