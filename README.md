# Regression-model-to-predict-house-prices
Regression model to predict house prices
Data Set Explanation:
Let's go through the columns in the given DataFrame:

ID: An identifier or a unique number assigned to each record in the dataset.

OverallQual: A rating or score representing the overall quality of the house. Higher values typically indicate better quality.

GrLivArea: The total living area (in square feet) above ground level, excluding the basement.

YearBuilt: The year the house was built.

TotalBsmtSF: The total area of the basement in square feet.

FullBath: The number of full bathrooms in the house.

HalfBath: The number of half bathrooms in the house.

GarageCars: The number of cars that can be accommodated in the garage.

GarageArea: The total area of the garage in square feet.

SalePrice: The sale price of the house.

YearsOld: A feature that is created during feature engineering. It represents the age of the house by subtracting the 'YearBuilt' from the current year.


Steps perfoamed to solve the problem Statement:
 
 Steps are following:

1. Importing the packages
2. Load the dataset
3. EDA
Display basic statistics of the numerical features
Correlation matrix heatmap
Pairplot for selected features
Boxplot for SalePrice based on OverallQual
Distribution plot for SalePrice
4. Feature Engineering
5. Split the data into training and testing sets
6. Define preprocessing steps
Create a preprocessor
7. Choose a regression algorithm
Create a pipeline with preprocessing and regression
8. Train the model
Make predictions on the test set
9. Evaluate the model
10. Example prediction for new data

Model Used: Linear Regression

Perfoamance Score:
Adjusted R-squared: -0.10420465149871427
Mean Squared Error: 17782193318.086823
R-squared: -0.05981451475504729
