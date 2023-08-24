#  Alegerian-Forest-fire-prediction

# Introduction

Forest fires pose a significant global challenge, resulting in the annual loss of millions of hectares. Algeria, like many nations, grapples with this issue, particularly during the summer season.Forest fire detection and forecasting become critical issues for reducing the disaster's damage. Exploration of new fire detection and forecast systems as alternatives to existing ones becomes a necessity. The goal is to predict whether or not the fire will break out based on weather data.

# This application is built to predict the Fire break out based on the below fields:
Attribute Information:

1. Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012)
Weather data observations

2. Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42
   
3. RH : Relative Humidity in %: 21 to 90
 
4. Ws :Wind speed in km/h: 6 to 29
 
5. Rain: total day in mm: 0 to 16.8

# FWI Components
6. Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
 
8. Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
 
10. Drought Code (DC) index from the FWI system: 7 to 220.4
 
12. Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
   
14. Buildup Index (BUI) index from the FWI system: 1.1 to 68
 
16. Fire Weather Index (FWI) Index: 0 to 31.1
    
12 Classes: two classes, namely Fire and not Fire
# Library Used in this Project

# Data Pre-Processing

Numpy, Pandas, Matplotlib, Seaborn

# Model Building
Sklearn

# Following  Step Perform in this project
1.Data Collection

2.Data Pre-Processing

3.Exploratory Data Analysis

4.Feature Engineering

5.Feature Selection

6.Model Building

7.Model Selection

8.Hyperparameter Tuning

9.Flask framework



# model Bulding
For regression analysis FWI(Fire weather Index) considered as dependent feature because it highly correlated with classes variable with more than 90% correlation.

Linear regression

Lasso Regression

Ridge Regression

Elastic Regression

# Model-selction
HyperParameter Tuning performed using RandomizedsearchCV for the model which performed best for  Regression.
For Regression r2_score metrics is used to select best model.

# model                           acuuracy

Linear                            98.47%

Lasso                            94.92 %

Ridge                            98.43%

Elastic                          87.53%

The best Mean Ridge Regression Model is used for Model Deployment

# Model  Deployment
 # FLASK
 framework is created using Flask.

 # FOR FRONTEND 
 HTML

 CSS

# Tools used
VS CODE 

Git

GitHub  
