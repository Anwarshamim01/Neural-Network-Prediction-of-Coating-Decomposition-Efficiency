# Neural Network Prediction of Coating Decomposition Efficiency

## Overview
This repository contains the implementation and analysis of a Multilayer Perceptron (MLP) model developed to predict the Decomposition Efficiency (DE) of a coating process based on various material and process parameters. The analysis is focused on exploring the influence of spray angle variations on DE while holding other factors constant.

## Dataset
The dataset used in this study includes the following parameters:
- `wt_mat_1_per`: Weight percentage of the primary material.
- `therm_cond_mat_1`: Thermal conductivity of the primary material.
- `spec_heat_cap_mat_1`: Specific heat capacity of the primary material.
- `mod_elas_mat_1`: Modulus of elasticity of the primary material.
- `tensile_str_mat_1`: Tensile strength of the primary material.
- `yield_str_mat_1`: Yield strength of the primary material.
- `melt_point_mat_1`: Melting point of the primary material.
- `wt_per_al2o3`: Weight percentage of Aluminum Oxide.
- `substrate_material`: Material of the substrate.
- `substrate_hv`: Hardness of the substrate.
- `substrate_roughness_ra`: Average roughness of the substrate's surface.
- `substrate_roughness_rz`: Maximum roughness depth of the substrate's surface.
- `deposition_temperature_celcium`: Deposition temperature.
- `spray_angle_deg`: Angle at which coating material is sprayed.
- `stand_off_distance_mm`: Distance between the spray nozzle and the substrate.
- `travel_speed_mm_sec`: Travel speed of the spray nozzle.
- `feedrate_g_min`: Feed rate of the coating material.
- `DE`: Decomposition Efficiency (target variable).

## Contents
- `notebooks/` - Jupyter notebooks demonstrating the data preprocessing, model training, prediction, and analysis.
- `data/` - Folder containing sample data used for the analysis.
- `src/` - Source code for preprocessing and model setup.
- `models/` - Trained neural network models saved as checkpoint files.
- `requirements.txt` - Required Python packages for replicating the analysis.

## Usage
To replicate the analysis:
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
