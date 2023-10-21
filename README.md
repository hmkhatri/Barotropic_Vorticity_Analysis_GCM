# Barotropic Vorticity Budget Analysis

The repository contains scripts for barotropic vorticity budget analysis using GFDL-MOM6 output. The analysis requires depth-integrated momentum equation diagnostics, which can be saved as output in the latest version of MOM6.

| Python Notebook | Content |
| --- | --- |
|[Save_Vorticity_Budget.ipynb](./Analysis/Save_Vorticity_Budget.ipynb) | Compute vorticity budget terms from depth-integrated velocity equation diagnostics |
| [Data_Regrid.ipynb](./Analysis/Data_Regrid.ipynb) | Regrid vorticity terms to regular lat-lon grid for coarse-graining using [FlowSieve](https://github.com/husseinaluie/FlowSieve) package |
| [Vorticity_coarse_grain.ipynb](./JAMES_Paper_Plots/Vorticity_coarse_grain.ipynb) | Scale-dependent vorticity analysis with coarse-graining |
| [Vorticity-gcm-filters.ipynb](./JAMES_Paper_Plots/Vorticity-gcm-filters.ipynb) |  Scale-dependent vorticity analysis with [gcm-filters](https://github.com/ocean-eddy-cpt/gcm-filters) package |
| [Bottom_pressure_torque.ipynb](./JAMES_Paper_Plots/Bottom_pressure_torque.ipynb) | Supporting information for justifying the methodology of calculating bottom pressure torque in a model |
| [Snapshot_vorticity.ipynb](./JAMES_Paper_Plots/Snapshot_vorticity.ipynb) | Vorticity snapshot plots |   
