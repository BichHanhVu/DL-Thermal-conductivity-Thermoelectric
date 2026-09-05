# A Unified Deep Learning Framework for Structure-Based Thermal Conductivity Prediction and Target-Driven Inverse Materials Design

This repository contains the data and source code associated with the study. CGCNN and GNN models are used to predict the experimental total thermal conductivity of thermoelectric materials directly from crystal structure and temperature. The trained models are then integrated with Extra Trees screening and CHGNet structure optimization to identify candidates with thermal conductivity close to a target value.

## Repository Files

| File | Description |
|---|---|
| `mp_cif_matched_data_TE_filtered_outlier.csv` | Dataset of 701 experimental records linked to 42 crystal structures |
| `TC_CGCNN.ipynb` | CGCNN training, evaluation, and prediction |
| `TC_Basic_GNN.ipynb` | GNN training, evaluation, and prediction |
| `TC_Inverse_Design_CGCNN.ipynb` | Inverse design workflow using CGCNN |
| `TC_Inverse_Design_Basic_GNN.ipynb` | Inverse design workflow using GNN |
| `inverse_design_CGCNN_Prototype_CHGNet_final_top20_ranked_by_TC_error_TC0p8_T300K.csv` | Top 20 candidates identified using CGCNN |
| `inverse_design_Basic_GNN_Prototype_CHGNet_final_top20_ranked_by_TC_error_TC0p8_T300K.csv` | Top 20 candidates identified using GNN |
