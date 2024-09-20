# CS 5173 (Deep Learning) 
### Homework 1: Linear Regression and Neural Network Regression  
```Level: Undergraduate```  
  
```Language: Python``` 


## Overview
This repository contains the code and DNN models for the ```Homework 1``` of the ```CS 5173``` ```Deep Learning``` course. The objective/goal of this project is to predict the Cancer Mortality Rates using both Linear Regression and Deep Neural Network (DNN) models.  

The dataset used in this project contains various health and demographic features, with the target label being ```TARGET_deathRate```.  

The homework involves testing different DNN model architectures and hyperparameters, comparing their performances, and reporting results.  

## Repository Structure  
* ```Linear Regression Screenshots```  
  The screenshots of the Linear Regression model for **Validation Data** as well as **Testing Data**.
* ```Model Evaluation Screenshots```  
  The screenshots of all the DNN models' results. The **.png** files are named as **model_name(learning_rate=X.XXXX)**.    
  All the DNN models were tested with ```epochs=100```  and ```batch_size=64```.  
* ```Homework_1_CS5173_AnayJoshi.ipynb```  
  The code of **Linear Regression** and all the **DNN models**, along with all the required outputs.
* ```Homework 1 - Anay Abhijit Joshi.pdf```  
  The answers to **Step 1**, **Step 2**, **Step 5**, and **Step 6**.  
* ```cancer_reg.csv```  
  The dataset used in this homework, containing health and demographic features along with the target label, **TARGET_deathRate**, used to predict the cancer mortality rates.  
* ```README.md```

## Deep Neural Network (DNN) models  
* ```DNN-16```  
* ```DNN-30-8```  
* ```DNN-30-16-8```
* ```DNN-30-16-8-4```
  

## Parameters in ``` test_model ``` function
* ```training_model```
* ```learning_rate```
* ```batch_size```
* ```epochs```

``` 
  The 'test_model' function uses keyword-only arguments, and all parameters are required.
  Ensure that you specify the parameter names when passing values.
```
  

## Instructions to Run  
* Clone this repository or Download ``` Homework_1_CS5173_AnayJoshi.ipynb ``` file.  
* Upload the data from ``` cancer_reg.csv ``` file.
* Modify the parameters in the ``` test_model ``` function, as per your requirements. Note that the ``` test_model ``` function requires ``` keyword-only arguments ```, so ensure you specify the parameter's name before passing its value.  

  - Incorrect Syntax  ❌  
  ``` test_model(DNN_16, 0.0001, 64, 100) ```  

  - Correct Syntax   ✅  
  ``` test_model(training_model=DNN_16, learning_rate=0.0001, batch_size=64, epochs=100) ```  
* After setting the desired parameters, please compile the code to see the results.  
