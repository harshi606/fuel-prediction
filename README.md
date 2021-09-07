# Mileage-prediction
predicting the mileage of a vehicle given the specifications.

in this project i am predicting the mileage of the vehicle with the data given.the dataset i am using to train my machine learning model is very famous and is taken from kaggle.the auto mpg dataset have columns like 

**mpg**: this is the mileage of the vehicle in miles per gallon,which i converted to kilometers per litre.\
**cylinders**: the number of cylinders in the engine.\
**displacement**:the engine capacity.this data was given in cubic inches which i converted to cubic centimeters\
**horsepower**:horsepower of the engine.\
**weight**: weight of the vehicle given in lbs which i converted into kgs.\
**acceleration**: the time(in seconds) it takes to reach 0-60mph.\
**model year**: the year the car was manufactured.in this column the value given was year%100.\
**origin**:origin of the car.three values are given in this column it can be American,European or Asian.\
**car name**: name of the car.

the link to the dataset is https://www.kaggle.com/uciml/autompg-dataset.

inputs in the web app:

**cylinders**:     no of cylinders\
**displacement**:  capacity of the engine in cubic centimeters (cc)\
**horsepower**:    horsepower\
**weight**:        in kgs\
**acceleration**:  the time(in seconds) it takes to reach 0-60mph.\
**model year**:    format(YYYY)\
**origin**:        select from the dropdown list.\
https://share.streamlit.io/harshi606/fuel-prediction/main/mileageapp.py

click this link to view the web application

# WHAT IS THERE IN THIS FILES ?

1. mileage_model.pkl - This is the model used for web integration.
2. untitled.ipynb - This is the trained model code.
3. mileageapp.py - This file contains the web integration using streamlit.
