# Sliding_Window_DL_IMU_MOCAP

[![DOI](https://zenodo.org/badge/506383720.svg)](https://zenodo.org/badge/latestdoi/506383720)

## Code and Dataset



## Database Attribute Information
There are 4 CSV files corresponding to IMU and MOCAP data
- IMU training set
- IMU evaluation set
- MOCAP training set
- MOCAP evaluation set.

In each file it will find the acceleration x, y, z corresponding to 2 IMU sensors. One placed on the left wrist and the other on the left ankle. Also, the acceleration x, y, z corresponding to 2 markers of the MOCAP. Both are placed in the same place that IMUs.

The label information corresponds to the three activities performed:
- 0 for walking
- 1 for sit-to-stand
- 2 for squatting.

These are the columns of the csv files:
- Trial number
- x1
- y1
- z1
- x2
- y2
- z2
- label
  
## Citation
Milagros Jaén-Vargas. (2022). mjaenvargas/Sliding_Window_DL_IMU_MOCAP: 1.0 (v.0.1.0). Zenodo. https://doi.org/10.5281/zenodo.6793650
