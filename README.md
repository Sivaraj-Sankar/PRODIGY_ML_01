# PRODIGY_ML_01
Linear Regression Model

## House Price Prediction with Linear Regression
### Overview
A simple linear regression model that predicts house prices based on the square footage of the house and the number of bedrooms and bathrooms. This project demonstrates the use of machine learning techniques to make predictions in the real estate domain.

### Prerequisites
Before you can run the model, ensure that you have the following dependencies installed:

* Python (3.6 or higher)
* NumPy
* pandas
* scikit-learn
* Jupyter Notebook (if you plan to use the provided Jupyter notebook)

### Dataset
The dataset used for training and testing the model can be found in 
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
It contains the following columns:

* SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
* MSSubClass: The building class
* MSZoning: The general zoning classification
* LotFrontage: Linear feet of street connected to property
* LotArea: Lot size in square feet
* Street: Type of road access
* Alley: Type of alley access
* LotShape: General shape of property
* LandContour: Flatness of the property
* Utilities: Type of utilities available
* LotConfig: Lot configuration
* LandSlope: Slope of property
* Neighborhood: Physical locations within Ames city limits
* Condition1: Proximity to main road or railroad
* Condition2: Proximity to main road or railroad (if a second is present)
* BldgType: Type of dwelling
* HouseStyle: Style of dwelling
* OverallQual: Overall material and finish quality
* OverallCond: Overall condition rating
* YearBuilt: Original construction date
* YearRemodAdd: Remodel date
* RoofStyle: Type of roof
* RoofMatl: Roof material
* Exterior1st: Exterior covering on house
* Exterior2nd: Exterior covering on house (if more than one material)
* MasVnrType: Masonry veneer type
* MasVnrArea: Masonry veneer area in square feet
* ExterQual: Exterior material quality
* ExterCond: Present condition of the material on the exterior
* Foundation: Type of foundation
* BsmtQual: Height of the basement
* BsmtCond: General condition of the basement
* BsmtExposure: Walkout or garden level basement walls
* BsmtFinType1: Quality of basement finished area
* BsmtFinSF1: Type 1 finished square feet
* BsmtFinType2: Quality of second finished area (if present)
* BsmtFinSF2: Type 2 finished square feet
* BsmtUnfSF: Unfinished square feet of basement area
* TotalBsmtSF: Total square feet of basement area
* Heating: Type of heating
* HeatingQC: Heating quality and condition
* CentralAir: Central air conditioning
* Electrical: Electrical system
* 1stFlrSF: First Floor square feet
* 2ndFlrSF: Second floor square feet
* LowQualFinSF: Low quality finished square feet (all floors)
* GrLivArea: Above grade (ground) living area square feet
* BsmtFullBath: Basement full bathrooms
* BsmtHalfBath: Basement half bathrooms
* FullBath: Full bathrooms above grade
* HalfBath: Half baths above grade
* Bedroom: Number of bedrooms above basement level
* Kitchen: Number of kitchens
* KitchenQual: Kitchen quality
* TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
* Functional: Home functionality rating
* Fireplaces: Number of fireplaces
* FireplaceQu: Fireplace quality
* GarageType: Garage location
* GarageYrBlt: Year garage was built
* GarageFinish: Interior finish of the garage
* GarageCars: Size of garage in car capacity
* GarageArea: Size of garage in square feet
* GarageQual: Garage quality
* GarageCond: Garage condition
* PavedDrive: Paved driveway
* WoodDeckSF: Wood deck area in square feet
* OpenPorchSF: Open porch area in square feet
* EnclosedPorch: Enclosed porch area in square feet
* 3SsnPorch: Three season porch area in square feet
* ScreenPorch: Screen porch area in square feet
* PoolArea: Pool area in square feet
* PoolQC: Pool quality
* Fence: Fence quality
* MiscFeature: Miscellaneous feature not covered in other categories
* MiscVal: $Value of miscellaneous feature
* MoSold: Month Sold
* YrSold: Year Sold
* SaleType: Type of sale
* SaleCondition: Condition of sale
  
### Usage
To run the linear regression model, follow these steps:

1. Clone this repository:

git clone https://github.com/Sivaraj-Sankar/PRODIGY_ML_01.git
cd PRODIGY_ML_01

2. Open the Jupyter Notebook provided (house_price_prediction.ipynb) to see a step-by-step demonstration of the model.

3. Alternatively, you can run the Python script directly:
python house_price_prediction.py
This will train the model, make predictions, and display the results.

### Model
The linear regression model used in this project is implemented using scikit-learn. It predicts house prices using a linear combination of the input features (square footage, bedrooms, and bathrooms).

### Results
The model's performance is evaluated using metrics like Mean Squared Error (MSE) and R-squared (R^2). You can find the evaluation results in the Jupyter Notebook or in the Python script's output.

### Future Improvements
This project is a basic demonstration of linear regression for house price prediction. There are several ways to enhance it:

Feature engineering to create more informative features.
Trying different regression algorithms.
Hyperparameter tuning for better model performance.
Expanding the dataset for more accurate predictions.
