# Predicting-House-Prices-In-Bengaluru
This notebook was created to predict the price of house in Bangalore. This notebook was used for submission in the hackathon.
2 types of models are created. Linear Regression model and a Deep Learning model. Deep Learning model gives a better performance than the Linear Regression model. 
Three approaches were tried:
1. Society column was removed because it had the most null values
2. In the second approach I have encoded the society column such that if the building is present inside the society we shall encode it as 1 otherwise as 0
3. In the third approach, the third locality also includes IT Sector area. (Places included in the IT parks)