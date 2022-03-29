# DDFEMFDMMaxwell

The directory contains data used in the production of results in the paper

L. Beilina, E. Lindström, A domain decomposition finite element/finite difference method
 for permittivity reconstruction from time-dependent scattered data in conductive media, submitted.

All tests in this paper have used data from online repository

E. Zastrow, S. K. Davis, M. Lazebnik, F. Kelcz, B. D. Veen, S. C. Hageness, Online repository of 3D Grid Based
Numerical Phantoms for use in Computational Electromagnetics Simulations,
https://uwcem.ece.wisc.edu/MRIdatabase/

The file ID_012204.zip  contains Matlab code for producing original  and sampled data used in adaptive C++/PETSc code.
To be able  use Matlab's code one need download data files
pval.txt
mtype.txt

for object with ID=012204 from online repository 
https://uwcem.ece.wisc.edu/MRIdatabase/


All inp-files can be visualized in paraview.

GeomTest1.zip contains following files which were used for generation of data on 3 times locally refined mesh for Test 1: epsref3.m (file with exact epsilon), sigmaref3.m  (file with exact sigma), ref3.inp (file with   finite element mesh). 

MeshesTest2.zip contains following files which were used for generation of data  on 3 times locally  refined meshes for Test 2: epsref3.m (file with exact epsilon), sigmaref3.m (file with exact sigma), ref3.inp (file with   finite element mesh ) 

Test1noise10.zip contains final results of reconstructed epsilon on different refined meshes.
Test2noise10.zip contains final results of reconstructed epsilon obtained on different locally refines meshes.

