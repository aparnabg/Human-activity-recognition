# Human-activity-recognition

This repository contains an implementation of a Convolutional Neural Network with Long Short-Term Memory (CNN-LSTM) architecture for Human Activity Recognition (HAR) using Wi-Fi Channel State Information (CSI) data.


## Introduction

The primary objective of this project is to recognize human activities based on Wi-Fi signal data. We explore the combination of spatial and temporal features by employing a CNN-LSTM architecture, which allows the model to capture both the spatial and temporal patterns present in the data.


We have used publicly available Wifi CSIdata for this. Data can be downloaded from : <https://data.mendeley.com/datasets/v38wjmz6f6/1>

## Optimizers Comparison

We conducted experiments to investigate the impact of various optimizers on the performance of the CNN-LSTM model. The following optimizers were evaluated:

- Adadelta
- Adagrad
- Adam
- RMSprop
- SGD
- Nadam

### Experimental Results

The model was trained and evaluated over 20 epochs using each optimizer. The experimental results revealed significant variations in model accuracy:

- **Minimum Accuracy**: 31%

- **Maximum Accuracy**: 95%

These results highlight the importance of selecting an appropriate optimization method when training deep learning models for HAR using Wi-Fi signal data.

## Report

For a detailed study of the models and the impact of various optimizers, please refer to [report.pdf](report.pdf).

## Conclusion

Our analysis indicates that while CNN models can capture spatial features effectively, they may struggle with understanding temporal features in the data. By incorporating LSTM layers into the architecture, we observed improved accuracy in predicting human activities using Wi-Fi CSI data.



