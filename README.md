## Instruction and setup

Run this command to get the necessary package (DUE) that we are using: 
```git submodule update --init --recursive```


To get the necessary data for the 4th experiment. Run `prepare_data_gefcom.sh`

## The classification experiments are accompanied in the following notebooks

  - **Deep Neural Networks, Deep Ensembles, & MC Dropout**
    
    - *1. DNN, Ensembles, Dropout.ipynb* 
    
  - **Gaussian Processes Classifier & Deep Kernel Learning**
    
    - *2. GPs & DKL.ipynb*
  
  - **Spectral-Normalized Gaussian Processes** 
    
    - *3. SNGP.ipynb*


## Regression experiment

- Apply SNGP, DUE and Exact GP to the GEFCom'14 dataset

  - *4. GEFCom\'14_regression_experiment*
  
&nbsp;

## Acknowledgements

  - https://github.com/google/uncertainty-baselines
  - https://www.tensorflow.org/tutorials/understanding/sngp
  - https://github.com/y0ast/DUE
