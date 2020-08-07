# Precipitation Estimates from Satellite and Ground-Based Sensors.
----
With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

> Saharia, Dhiraj, et al. “Precipitation Estimates from Satellite and Ground-Based Sensors.”

The work is performed on Jupyter Notebooks and following packages were used -
- `pandas` - For data preprossesing.
- `matplotlib`, `seaborn`- For plotting.
- `glob` - For selecting multiple files.
- `xarray` - To work with `netCDF` files.
- `tslearn` - To compute the DTW scores and path.
- `scipy` - To use `cdist` for DTW path computation.



Directory Structure -
- `Figures/` - Contains all the figures and plots used in the paper.
- `data/` - Contains Gauge, GPM, and CHIRPS data.
- `01_Singapore_prat.ipynb` - Main notebook.

## Note:
The PRAT dataset used in this project can not be disclosed due to external reasons. However, one may feel to use/modify the code as per the requirement.
