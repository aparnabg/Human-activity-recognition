# Human-activity-recognition

This work shows how a combination of Wi-Fi Channel State Information (CSI) and Deep Learning can be used for Human Activity Recognition(HAR). 

We have used publicly available Wifi CSIdata for this. Data can be downloaded from : 

## Model
I have implemented cnn model to the data.  By analysing the CNN model, I had a conclusion that the CNN model can't understand entirely the data because it has temporal features along with the spatial features, that why adding LSTM layers to the data gives more accurate predictions.	

## various optimizers
Here, we investigate the impact of various optimizers on the performance of a Convolutional Neural Network with Long Short-Term Memory (CNN-LSTM) architecture for Human Activity Recognition (HAR) using Wi-Fi Channel State Information (CSI) data. We employ a range of optimizers, including Adadelta, Adagrad, Adam, RMSprop, SGD, and Nadam, to train and evaluate the model over 20 epochs. Our experimental results demonstrate significant variations in model accuracy, with values ranging from 31\% to 95\%. This study explains how choosing different optimization methods affects how well deep learning models work for recognising human activities using Wi-Fi signal data.

Details study of the models and impact of various optimizers can be found in report.pdf



