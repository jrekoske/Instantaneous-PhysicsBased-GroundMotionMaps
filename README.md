# Instantaneous-PhysicsBased-GroundMotionMaps
This is the public repository for the paper
"Instantaneous physics-based ground motion maps using reduced-order models",
John M. Rekoske, Alice-Agnes Gabriel & Dave A. May submitted to
Journal of Geophysical Research: Solid Earth (2022).

The preprint for this work is available on arXiv at [https://arxiv.org/abs/2212.11335](https://arxiv.org/abs/2212.11335).

In this repository, we provide the simulated PGV maps, available in the
`pgv_data` folder as HDF5 files. The files `loh.hdf5`, `3d_1400.hdf5`, and
`3d_500a.hdf5` correspond to the three forward models described in the
paper (LOH, 3D-1400, and 3D-500A).

We also provide a demo Jupyter notebook
`demo.ipynb` which shows how to access the data and use radial basis function interpolation
to create a reduced-order model.
