# Data Market Design through Deep Learning

This folder containts the implementation of the paper "Data Market Design through Deep Learning"

## Getting Started

The code is written in python and jupyter notebooks and requires the following packages:
- Numpy
- Scipy
- Matplotlib
- Pytorch

## Running the experiments

### Single-Buyer Settings
The notebooks in the RochetNet folder has all jupyter notebooks needed to recover the results in the main paper and appendix. The hyperparamters are set already in the cell that defines the config class. To recover the results that show how differential informativeness varies for the enlarged buyer type, go to RochetNet/enlarged_types/Enlarged_types_mix.ipynb and change the values corresponding to `cfg.v_L` to vary `a` and re-run the notebook.

### Multi-Buyer Settings

#### BIC Settings
The notebooks in the BIC folder has all jupyter notebooks needed to recover the results in the main paper and appendix. The hyperparamters are set already in the cell that defines the config class. To recover the results computing how revenue varies $\alpha$, go to BIC/uncertain_theta/UNF_NE.ipynb and BIC/uncertain_v/U_theta_0.50_alpha_0.50.ipynb and set `cfg.alpha` to the appropriate value and re-run the experiments 

#### *Ex post* IC settings
The notebooks in the IC folder has all jupyter notebooks needed to recover the results in the main paper and appendix. The hyperparamters are set already in the cell that defines the config class. 
