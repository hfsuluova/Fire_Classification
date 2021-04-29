# Assignment
This Repo includes notebooks regarding University of Essex - CE888 - Data Science and Decision Making module Assignment2.
The dataset used in this study can be found in the following link: https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs


## Main.ipynb 
includes a simple CNN model trained from scratch and some basic Exploratory Data Analysis.

-Loading Data

-Creating datagens

-Image Distribution

-Image Features (batch_size, size, channel)

-Sample Images

-Modelling

-Compiling

-Model Training

-Loss and Accuracy Histograms Regarding Training

-Prediction Accuracy

-Confusion Matrix(Faulty)

## MobileNet.ipynb
includes a transfer learning approach. It uses pre-trained MobileNet CNN.

-Loading Data

-Creating datagens

-Loading MobileNet Model

-Summary of MobileNet Model

-Replacing the last 5 layers with Dense layer

-Summary of New Model

-Compiling

-Model Training

-Loss and Accuracy Histograms Regarding Training

-Prediction Accuracy

-Confusion Matrix

## Inception_with_ReducedData.ipynb
includes a transfer learning approach with reduced number of data. 

-Printing Number of Images (reduction is done by split_helper.ipynb)

-Creating datagens

-Loading InceptionV3 Model

-Summary of InceptionV3 Model

-Adding 4 more layers 

-Summary of New Model

-Compiling

-Model Training

-Loss and Accuracy Histograms Regarding Training

-Prediction Accuracy

-Confusion Matrix
