Based on a csv file of King's County housing data, three unique models were created to better understand this data.

##Data Preparation

### Imports
First we imported the necessary packages, methods, and graphical settings necessary for the project

### Data Cleaning
The dataframe was set to a variable.
Columns had their null values filled.
Categorical values were in a state where they would negatively impact the model so they were adjusted.
The highest correlated columns were found.

## Models

### OLS Regression
Ordinary Least Sqaures, r-squared value, p-value and more important observations of the models were found.
The data was organized with 66% of the data was for training and 33% of it was for testing.
The Mean Squared Error of each model's test-train data was calculated.

### Model Results

#### Model 1
At an r-squared value of 0.592, this model was not accurate enough.

#### Model 2
At an r-squared value of 0.807, this model met requirements of accuracy.

#### Model 3
This model used information from the other two models and had the highest r-squared value, 0.833