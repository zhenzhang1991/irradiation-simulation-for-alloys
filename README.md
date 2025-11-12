For simulating the irradiation response of a alloy system, we use the EAM potential which was smoothly 
joined to the Ziegler–Biersack–Littmark (ZBL) potential for small interatomic separations. 

Details for the ZBL-implementation can be found in the pair_eam_alloyZBL.cpp file which should be placed 
into the src folder of your LAMMPS installation path together with the pair_eam_alloyZBL.h before compilation.

Also included is an example LAMMPS input file for performing the PKA simulations and the file to be loaded
for defining electron stopping.

Reference: 
Zhen Zhang, Zhengxiong Su, Bozhao Zhang, Qin Yu, Jun Ding, Tan Shi, Chenyang Lu, Robert O. Ritchie, and Evan Ma. 
Effect of local chemical order on the irradiation-induced defect evolution in CrCoNi medium-entropy alloy. 
Proc. Natl. Acad. Sci. U.S.A. 120, e2218673120 (2023).
