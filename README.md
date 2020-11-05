# Precipitation Estimates from Satellite and Ground-Based Sensors.
----
With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript:

> Saharia, Dhiraj, et al. “Precipitation Estimates from Satellite and Ground-Based Sensors.”

The work is performed on Jupyter Notebooks and following packages were used -
- `pandas` - For data pre-processing.
- `matplotlib`, `seaborn`- For plotting.
- `glob` - For selecting multiple files.
- `xarray` - To work with `netCDF` files.
- `tslearn` - To compute the DTW scores and path.
- `scipy` - To use `cdist` for DTW path computation.

Data - `https://drive.google.com/drive/folders/1Fw-7wc1sguI4i5_uNcl7mkUV1KcDNs6n?usp=sharing`

Directory Structure -
- `Figures/` - Contains all the figures and plots used in the paper.
- `data/` - Contains Gauge, GPM, and CHIRPS data.
- `01_Singapore_prat.ipynb` - Main notebook.

## Note:
The PRAT dataset used in this project can not be disclosed due to external reasons. However, one may feel to use/modify the code as per the requirement.
