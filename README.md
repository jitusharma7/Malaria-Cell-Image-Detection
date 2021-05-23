# Malaria-Cell-Image-Detection
The purpose of this project is to analyze the images of human cells using convolutional neural networks and classify them as parasitized or uninfected.


## Table of Content
  * [Overview](#Overview)
  * [Problem_Definition](#Problem_Definition)
  * [Dataset_Description](#Dataset_Description)
  * [Data Preprocessing](#Data_Preprocessing)
  * [Building CNN](#Building_CNN)
  * [Model_Building](#Model_Building)
  * [Result](#Result)
  * [Business_Recommendation](#Business_Recommendation)
  * [Credit](#Credit)
  
## Overview
Malaria is a serious global disease and a leading cause of morbidity and mortality in tropical and sub-tropical countries. It affects between 200 and 300 million people and causes more than 1 million deaths every year. It becomes the 5th cause of death from infectious diseases worldwide in low-income countries. Yet, malaria is both preventable and curable. How AI can be leveraged for detecting malaria, a deadly disease, and focus on building a low-cost, yet effective and accurate open-source solution  For which, it is important to develop an automated image analysis that can identify the uninfected and infected RBCs in a blood smear image. 
 
 ## Problem_Definition
A general framework to perform detection of the malarial parasite, which includes image preprocessing, extracting infected blood cells, morphological operation, and highlighting the infected cells is described. This methodology may serve as a rapid diagnostic tool for malaria, even where the expert in the microscopic analysis may not be available.  
Currently, clinical diagnosis primarily utilizes microscopy to study the prepared blood Sample. However, evaluation of sample is Difficult and time-consuming, especially in situations where large numbers of samples require reliable analysis.

 
 ## Dataset_Description
Source of dataset – Official NIH Website, Malaria Cell image Dataset 
This dataset consists of 27,558 images of microscopic blood samples
The data set contains two folders-Parasitized and Uninfected.

<img src="/Malaria_Uninfected.PNG" width="300">
<img src="/Malaria_Infected.PNG" width="300">


## Data Preprocessing
*Data preprocessing for Malaria dataset involves resizing and rescaling of training and testing data using ImageDataGenerator package and then giving specifications to both datasets
### Steps to Data Preprocessing
1. Image Rescaling for both training and testing data set
2. Applying predefined specification to training and testing dataset


## Building CNN
### Steps to Build Convolutional Neural Network
1. Import required libraries
2. Initialize CNN and add a Convolutional layer
3. Pooling
4. Add two convolutional layer
5. Flattening
6. Fully connected layer and output layer

<img src="/Builiding%20CNN.PNG" width="300">


## Model_Building
### Steps to model Building
1. Compile the CNN model
2. Training the CNN on the Training set
3.  Evaluating on Testing set
4.  Comparison of accuracy and loss function


    
## Result
1. The accuracy of the model is 96.82%. The accuracy of the model should be next to 100% in medical domain problems.
2. Loss is the penalty for a bad prediction. The aim is to make the validation loss as low as possible.

## Business_Recommendation
* CNN's are best for image classification and give superb accuracy. Also, computation is much less compared to simple ANN.
* The algorithm generated will be helpful in the area where the expert in the microscopic analysis may not be available.

## Credit
This project has been done as a course project on CNN deep learning technique.

