# House Price Prediction with Linear Regression

## OASIS INFOBYTE - Level 2 Task 1

## Objective

Build and evaluate machine learning models to predict house prices based on different property features using Linear Regression and Ridge Regression.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains information about residential properties, including:

- Area
- Bedrooms
- Bathrooms
- Floors
- YearBuilt
- Location
- Condition
- Garage
- Price

The `Id` column was excluded from the prediction features because it is only an identifier.

## Data Analysis Performed

- Dataset inspection
- Missing-value analysis
- Duplicate detection
- Descriptive statistics
- Exploratory Data Analysis (EDA)
- Price distribution analysis
- Correlation analysis
- Feature selection
- Categorical feature encoding

## Machine Learning Process

- Selected numerical and categorical features
- Applied One-Hot Encoding to categorical variables
- Split the dataset into 80% training and 20% testing data
- Built a Linear Regression model
- Generated house price predictions
- Evaluated model performance
- Performed residual analysis
- Analyzed model coefficients
- Built a Ridge Regression model
- Compared Linear Regression and Ridge Regression

## Evaluation Metrics

The models were evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Lower MSE and RMSE indicate better prediction performance, while a higher R² Score indicates a better model fit.

## Visualizations

The project includes visualizations for:

- House price distribution
- Area analysis
- Bedrooms analysis
- Year Built analysis
- Location analysis
- Condition analysis
- Garage analysis
- Correlation heatmap
- Actual vs Predicted prices
- Residual analysis
- Model comparison

## Models Used

### Linear Regression

Linear Regression was used as the primary model for predicting house prices based on the selected property features.

### Ridge Regression

Ridge Regression was implemented as an additional model and compared with Linear Regression using the same evaluation metrics.

## Key Insights

The analysis demonstrates how property characteristics such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage can be used as features for house price prediction.

Model performance was compared using MSE, RMSE, and R² Score.

## Conclusion

This project demonstrates the complete machine learning workflow for house price prediction, from data exploration and preprocessing to model training and evaluation.

Linear Regression and Ridge Regression were developed and compared to understand their performance in predicting house prices. The project provides practical experience in data analysis, feature preprocessing, regression modeling, visualization, and model evaluation.
