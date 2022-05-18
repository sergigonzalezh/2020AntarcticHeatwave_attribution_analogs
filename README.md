# 2020AntarcticHeatwave_attribution_analogs.py

This is the Jupyter notebooks required to reproduce the research published in *Communications of Earth & Environment*.

This repository is divided in different notebooks that:
  - 0a. Download the ERA5 datasets used in this research
  - 0b. Prepare the ERA5 dataset (mean daily temperatures)
  - 1a. Compute and plot the anomalies and percentiles of the 2020 Heatwave
  - 1b. Compute and plot the past-recent distribution and trends of tempearture in the Antarctic Peninsula
  - 2a. Compute and plot temperature anomalies at different stations
  - 3a. Compute and plot the flow analogs, and the temperature differences between the past and recent periods
  - 3b. Compute and plot the flow analogs, and the temperature differences between the past and recent periods (SAM effect removed)
  - 3c. Compute and plot the flow analogs, and the temperature differences between the past and recent periods (Detrended)

More information at: González-Herrero et. al. (2022)
DOI: https://doi.org/10.1038/s43247-022-00450-5

## Versions and dependences

The script consists in a group of Jupyter notebooks programed in python 3.8. The following libraries are necessary:
```
  cdsapi
  os
  argparse
  netCDF4
  scipy
  numpy
  pandas
  seaborn
  matplotlib  
  cartopy
```

## How to cite

If you use or modify this script for your research, please cite as:

Citation

## Contact
If you have any question, please contact with Sergi at sergi.gonzalez@meteo.ub.edu
