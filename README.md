# InstantaneousPhysicsBased-GroundMotionMaps
This is the public repository for the paper,

Rekoske, J. M., Gabriel, A. A., & May, D. A. (2023). Instantaneous physics‐based ground motion maps using reduced‐order modeling. 
Journal of Geophysical Research: Solid Earth, 128(8), e2023JB026975. <https://doi.org/10.1029/2023JB026975>.

In this GitHub repository, we provide the simulated PGV maps, available in the
`pgv_data` folder as HDF5 files. The files `loh.hdf5`, `3d_1400.hdf5`, and
`3d_500a.hdf5` correspond to the three forward models described in the
paper (LOH, 3D-1400, and 3D-500A).

We also provide a demo Jupyter notebook
`demo.ipynb` which shows how to access the data and use radial basis function interpolation
to create a reduced-order model.
