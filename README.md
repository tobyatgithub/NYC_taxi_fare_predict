# NYC_taxi_fare_predict
Author: Toby  

### **General description:**  
This repository contains my code for [Kaggle NYC taxi fare challenge](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction) using tensorflow to load and preprocess 55 million records in batches. And use them for a Linear regressor and a DNN regressor. RSME was found to be around 3.6.  

The main challenge of this project comes from 2 parts:  
1. the large size of data.  
2. hyper-tunning a model with such amount of data  
I batched the data to read and preprocess, and used tensor board and continue training to train and tune the DNN regressor.  
