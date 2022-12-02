# Instantaneous-PhysicsBased-ShakeMaps
This is the public repository for the paper
"Instantaneous physics-based ShakeMaps, achieved by surrogate modeling of HPC simulations",
John M. Rekoske, Alice-Agnes Gabriel & Dave A. May submitted to
Journal of Geophysical Research: Solid Earth (2022).

The PGV data are stored in the `pgv_data` folder, which contains two
HDF5 files for the LOH and 3D+TOPO simulated data. We also provide a
Jupyter notebook `demo.ipynb` which demonstrates how to access the simulated data
and create a reduced-order model using radial basis function interpolation.

To install the necessary packages for the demo notebook, please run `pip install -r requirements.txt`
