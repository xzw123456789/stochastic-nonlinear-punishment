# The stochastic nonlinear punishment in public goods games

This repository contains the source code and data for the numerical simulations presented in the paper **"The stochastic nonlinear punishment in public goods games."**

## Environment Requirements
* **Software:** MATLAB
* **Version:** 2021b or later
* **Note:** The Monte Carlo simulations are implemented in C++. Please note that these simulations may require a significant amount of time to complete.

## Code Mapping
The following scripts and folders correspond to the figures in the paper:

| File/Folder | Corresponding Figure | Notes |
| :--- | :--- | :--- |
| `x_dot_well` | **Figure 2** | |
| `f1_0_r` | **Figure 3a** | |
| `f_x_0` | **Figure 3b** | |
| `structure_f0_0_f1_0` | **Figure 4** | Panel (a): $r=0.5$; Panel (b): $r=8.5$ |
| `structure_f1_0` | **Figure 5** | |
| `Folder_Fig6_code` | **Figure 6** | Monte Carlo simulation code |
| `Folder_Fig7_code` | **Figure 7** | Monte Carlo simulation code |
| `Folder_Fig6_data` | **Figure 6** | Monte Carlo simulation data |
| `Folder_Fig7_data` | **Figure 7** | Monte Carlo simulation data |

## Usage
1. Ensure all MATLAB files are in your working directory.
2. Run the specific script corresponding to the figure you wish to replicate.
3. For Monte Carlo simulations (Figures 6 and 7), refer to the source files within their respective folders.
