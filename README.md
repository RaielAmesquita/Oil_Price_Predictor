# Oil_Price_Predictor
Use Python and Jupyter Notebook to predict the price of crude oil. 

I live in the Permian Basin which is also known as the energy capital of the United States. On average, 4 million barrels of oil are extracted every day.
The purpose of this project is to predict the price of crude oil. 

Predicting markets are the most exciting projects to perform as a student of data science. One can tell can tell a lot about the state of an area depending 
on how well certain markets are performing. The challenge is to use machine learning in Python to predict the price of crude oil in the permian basin. 

Theory - I will apply a linear regression model to 20 years of data to predict the price of oil. Regression is one of the many algorithms in machine learning 
that can be trained to predict certain real-numbered results. The prediction is based on the interaction of the different variables found in the dataset.

Data - I used Yahoo Finance and Quandl for the necessary data sets. I used crude oil prices from January 1, 2000 to January 1, 2020. 

Variables -  The dependent variable in this case will be the price of the oil we are trying to predict. The independent variable also our predictor variable, 
will be the moving averages for the past three and nine days. 

Cleaning the data - It is important to only keep the data that is necessary. After initializing the x and y variables, we will drop all the NaN values to 
help clean the data.  

Training - We are going to set 80% of our data into a training set, responsible for training the model. The other 20% will be assigned to a testing set. 
The testing set will be used to estimate the accuracy of the model. By connecting the input from the training set with the expected result from the testing set, 
we create a linear regression model. Then we are going to fit the x and y variables in the model and create a constant and a coefficient for the regression. 

Accuracy- After the training stage is complete we can use compute() function to test the accuracy of the model. 

