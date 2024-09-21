
# Car Price Prediction

![car](https://github.com/user-attachments/assets/7d4304bb-6c07-46a3-99e0-ab70bb5de8fb)

This project focuses on predicting the selling price of used cars based on various features using machine learning techniques. The dataset contains essential car attributes, such as the year of manufacture, current price, kilometers driven, fuel type, and others, which influence the selling price.

## Dataset

The dataset includes the following columns:

- **Year**: Year the car was manufactured.
- **Selling_Price**: Price at which the car is being sold.
- **Present_Price**: Current ex-showroom price of the car.
- **Driven_kms**: Total kilometers driven by the car.
- **Fuel_Type**: Type of fuel used by the car (Petrol, Diesel, CNG).
- **Selling_type**: Type of seller (Dealer or Individual).
- **Transmission**: Type of transmission (Manual or Automatic).
- **Owner**: Number of previous owners.
- **No_of_Years**: Number of years since the car was manufactured.

## Project Workflow

1. **Data Preprocessing**: 
   - Addressed missing and duplicated values.
   - Dropped irrelevant features and transformed certain features for better model performance.
2. **Exploratory Data Analysis (EDA)**: 
   - **Univariate analysis**: Histogram, distplots, and summary statistics for understanding individual features.
   - **Bivariate analysis**: Correlation analysis, scatter plots, and trend lines to examine relationships between variables.
3. **Outlier Detection**: Applied techniques such as Box-Cox transformation to normalize skewed data and address outliers.
4. **Model Building and Evaluation**: 
   - **Gradient Boosting**: Achieved the highest R-squared score of **0.97**.
   - **Decision Tree**: Produced a competitive R-squared score of **0.96**.
   - **Lasso Regression**: Useful for feature selection with an R-squared of **0.95**.
   - **Linear Regression**: Performed similarly with an R-squared of **0.96**.
   - 
   - ![predicted](https://github.com/user-attachments/assets/f798f9d4-1b85-41c1-869c-217c197d4134)

## Visualizations

Here is a sample correlation heatmap, showing the relationships between key features:

![correlation](https://github.com/user-attachments/assets/0edd586d-26d0-40dc-bcc9-a93acbeefd4f)

