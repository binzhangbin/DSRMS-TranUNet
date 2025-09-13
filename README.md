# DSRMS-TranUNet
# 🧠 Code Pre-release Statement  

**This repository contains the official implementation for the paper "DSRMS-TransUNet: A Decentralized Non-Shifted TransUNet for Shallow Water Acoustic Source Range Estimation"**  

## 📜 Current Status  
- 🔒 Core code and experimental data are temporarily withheld to ensure data security and privacy  
- 📊 All experimental results in the paper were obtained using the complete implementation in this repository  
- ⚙️ Model architecture details are described in Section 2 (Proposed Method) of the paper  

## 🚀 Release Plan  
| Stage | Content | Timeline |
|-------|---------|----------|
| Paper Acceptance | Open-source basic framework code | Within 24 hours of acceptance |
| Formal Publication | Release complete training/inference code | Upon paper online publication |
| Supplementary Verification | Public benchmark dataset release | Within 24 hours of publication |

## 🔍 Future Contents  
```bash
├── core_architecture/                 # Backbone 
│   ├── dstransunet.py                 
│   └── rvit.py                        
│   ...                                # Other benchmark network models 
├── pretrained_models/                 # Pre-trained weights
│   ├── simulation_dsrmstransunet.pth  # Simulation model for testing
│   └── hlah_dsrmstransunet.pth        # SWellEx-96 HLAH model for testing
│   └── hlas_dsrmstransunet.pth        # SWellEx-96 HLAS model for testing
├── training_scripts/                  # Training scripts
│   ├── main_simulation_train.py       # Main script for simulation data training
│   ├── main_real_train.py             # Main script for measured data (SWellEx-96 HLAH and HLAS) data training
│   └── utils_load_dataset.py          # Parameters for data loading
└── test_scripts/                      # Testing scripts
│    └── main_simulation_test.py       # Main script for simulated data testing
│    └── main_real_test.py             # Main script for measured data (SWellEx-96 HLAH and HLAS) testing
├─── ...                               # Plot and evaluation methodology: Accurate, RMSE, Distribution, stratified K-fold cross-validation

