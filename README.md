# DSRMS-TranUNet
# 🧠 Code Pre-release Statement  

**This repository contains the official implementation for the paper "DSRMS-TransUNet: A Decentralized Non-Shifted TransUNet for Shallow Water Acoustic Source Range Estimation"**  

## 📌 Code Availability Notice
&gt; **Note:** The repository is currently under reorganization.
&gt;
&gt; Part of the implementation in this work is closely related to our ongoing
&gt; follow-up research and is being refactored and cleaned up. Therefore, the
&gt; complete source code, pretrained models (.pth), and test data are
&gt; **temporarily not fully available** in this repository. We will update this
&gt; repository once the related work is finished.
&gt;
&gt; In the meantime, if you need access to the **complete code, pretrained
&gt; weights (.pth), and test data** of this paper, please contact:
&gt;
&gt; 📧 **zhangbin9145@stu.ouc.edu.cn**
&gt;
&gt; Please indicate your affiliation and the purpose of your request in the
&gt; email, and we will get back to you as soon as possible.

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

