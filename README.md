# House Price Prediction Using Machine Learning
## Introduction
This project aims to predict house prices based on various features such as location, size, number of bedrooms, bathrooms, and other relevant 84 features. The model employs a Decision Tree Regressor (DTR), a supervised machine learning algorithm, to analyze patterns in the dataset and provide accurate predictions.


`About the Meta Data:`

## Column Descriptions:

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- MasVnrArea: Masonry veneer area in square feet
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinType2: Quality of second finished area (if present)
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of basement area
- TotalBsmtSF: Total square feet of basement area
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second floor square feet
- LowQualFinSF: Low quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- KitchenQual: Kitchen quality
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Functional: Home functionality rating
- Fireplaces: Number of fireplaces
- FireplaceQu: Fireplace quality
- GarageType: Garage location
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea**: Size of garage in square feet
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- PoolQC: Pool quality
- Fence: Fence quality
- MiscFeature: Miscellaneous feature not covered in other categories
- MiscVal: Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold
- SaleType: Type of sale
- SaleCondition: Condition of sale

## Project Workflow:
### 1. Data Collection:
Collect a dataset containing house features and corresponding prices.
Example: Datasets can be sourced from Kaggle, public repositories, or real estate APIs.
### 2. Data Preprocessing:
Handling Missing Values: Fill or remove missing data to ensure the dataset is complete.
Feature Engineering:
Convert categorical variables (e.g., city, neighbourhood) into numerical data using encoding techniques like one-hot encoding or label encoding.
Scale numerical features for better model performance.
Data Splitting:
Split the dataset into training and testing sets, typically in a ratio of 80:20.
### 3. Exploratory Data Analysis (EDA):
Analyze relationships between house features and price using visualizations (e.g., scatter plots, box plots).
Identify outliers and correlations to guide feature selection.
### 4. Model Implementation:
Algorithm Selection:
Use Decision Tree Regression due to its ability to handle non-linear relationships and its interpretability.
Hyperparameter Tuning:
Optimize parameters like max_depth, min_samples_split, and min_samples_leaf using techniques such as Grid Search or Random Search.
### 5. Model Training:
Train the Decision Tree Regressor on the training data.
Use the features as input and the house prices as output labels.
### 6. Model Evaluation:
Evaluate the model's performance on the testing set using metrics such as:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
If needed, compare the DTR's performance with other regression models (e.g., linear regression, or Random Forest Regression).
### 7. Deployment (Future Work):
Create an API or web application to take house feature inputs and output predicted prices.
Tools for deployment: Flask, Django, or FastAPI for backend development.

## Advantages of Decision Tree Regression:
Non-Linear Relationships: Captures complex, non-linear relationships between features and the target variable.
Interpretability: Decision Trees clearly represent how predictions are made through their branching structure.
No Need for Scaling: DTR does not require feature scaling (e.g., standardization or normalization).

## Output
![output](https://github.com/user-attachments/assets/2c4d5541-5ec9-4842-b486-345c923dc3e7)

