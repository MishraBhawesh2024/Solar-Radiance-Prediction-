Data Description

Meteorological data from the HI-SEAS weather station Duration of four months (September through December 2016) between Missions 4 (IV) and 5 (V). Source: https://www.kaggle.com/datasets/dronio/SolarEnergy

The units of various columns:

Solar radiation: watts per meter^2
Temperature: degrees Fahrenheit
Humidity: percent
Barometric pressure: Hg
Wind direction: degrees
Wind speed: miles per hour
Sunrise/sunset: Hawaii time
TABLE OF CONTENTS:

Library Import and Data Loading

Data Preprocessing

a. Checking for null-values b. Checking class balance

Exploratory Data Analysis:

a. Correlation Matrix b. SelectKBest

Feature Engineering:

Prepping the data for ML

Prediction using ML

Our goal is to build a prediction model that efficiently relates independent variables (some already present and some extracted) to predict 'Radiation'.
