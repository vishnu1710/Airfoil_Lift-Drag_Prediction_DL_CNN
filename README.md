# Deep Learning CNN-based aerodynamics parameters prediction method
CNN for airfoil lift-to-drag-ratio prediction

This repository contains data, code, and results for implementing an airfoil lift-to-drag ratio prediction method based on Convolutional Neural Network. The network model can take into cnn model `the airfoil contour` and predict its `areodynamics parameters` such as lift-to-drag ratio.  
## Model Architecture:_   
The data has been taken from the work of Zi Li [@Zili] (https://github.com/ziliHarvey/CNN-for-Airfoil) and I modified the CNN using Keras and Tensorflow. 

**Model building:**   This CNN models runs 5000 times faster than commercial CFD software with relative low error (i.e Test MSE 0.002 after 50 epoch's training)


## _Contents_  
**/data/raw_data/foil_figure.rar:**   
&emsp;a file of all filled-in grayscale airfoil contour figures generated from coordinates txt files from [UIUC Airfoil Data Site](https://m-selig.ae.illinois.edu/ads/coord_database.html).  
**/data/raw_data/csv.zip:**  
&emsp;a file of all samples' lift-to-drag ratio calculated by Xflr5
**/data/parsed_data/1_300.mat**  
&emsp;the above raw data is parsed into .mat file for loading  
&emsp;Please unzip raw data and modify directory and then run it.   


 <img src="https://github.com/ziliHarvey/CNN--based-aerodynamics-parameters-prediction-method/raw/master/cnn.png">

## _Result_
 <p align="left">
 <img src="https://github.com/ziliHarvey/CNN--based-aerodynamics-parameters-prediction-method/raw/master/result/loss_vs_epoch.png" width="50%" height="50%">
 <img src="https://github.com/ziliHarvey/CNN--based-aerodynamics-parameters-prediction-method/raw/master/result/local_result.png" width="50%" height="50%">
 </p>

## _Licence_  
The source code is released under MIT Licence.  

