[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) 

## Machine learning full 3-D lower-body kinematics and kinetics on patients with osteoarthritis from electromyography
https://www.sciencedirect.com/science/article/pii/S266709922300018X

## Overview
Twenty-four subjects were recruited for this study. The subjects were approved by the University of Missouri internal review board (IRB #1212807) and all subjects provided informed consent. 

![Scheme of the prediction model](https://ars.els-cdn.com/content/image/1-s2.0-S266709922300018X-gr1_lrg.jpg)


We designed an RNN model for estimating lower body joint angles (JAs) and ground reaction forces (GRFs) from surface-EMG sensors during a step-down task for individuals diagnosed with OA. 


## Model hyperparameters
Recurrent Neural Network (RNN)
Optimizer: sgd; 
Loss: MSE
Metrics: RMSE
RNN Layer: (512,1)
Embedding Layer: (512,20)
Batch Normalization: (512,20)
1D Convolution Layer: (101,20)
Dense Layer: (101,20)