# Housing Data Analysis and Prediction

This project involves analyzing housing parcel data, performing extensive data cleaning and preprocessing, and applying a neural network model to predict housing prices. Below is a summary of the key steps and methodologies employed.

## Project Overview

- **Data Source:** Housing parcel data Mecklenburg County Open data Portal.
- **Objective:** Clean and preprocess the data, analyze key features, and build a neural network model to predict housing prices.

## Key Steps

1. **Data Import and Initial Inspection:**
   - Loaded the dataset and displayed basic information about the columns and their data types.
   - Visualized the distribution of 'Divide' categories using bar plots.

2. **Data Cleaning:**
   - Calculated the percentage of null values for each column and dropped columns with more than 30% missing values.
   - Removed specific unwanted columns to streamline the dataset.

3. **Feature Engineering:**
   - Created an 'Age' column based on the year the house was built.
   - Renamed specific categorical values for consistency.
   - Applied label encoding to transform categorical variables into numerical ones.

4. **Data Filtering and Consolidation:**
   - Filtered the dataset to include only Single-Family, Multi-Family, and Condo/Townhome properties.
   - Dropped original categorical columns after transformation.

5. **Statistical Analysis:**
   - Generated a correlation matrix to understand relationships between features.
   - Plotted the distribution of housing prices and performed a QQ plot to check the normality of the price distribution.
   - Calculated skewness and kurtosis for the housing prices.

6. **Modeling:**
   - Built and trained a neural network using TensorFlow and Keras to predict housing prices.
   - Split the data into training and testing sets, and evaluated model performance using Mean Squared Error (MSE).

## Results

- **Visualization:** Used Seaborn and Matplotlib for data visualization.
- **Neural Network:** Implemented a neural network with two hidden layers to predict housing prices, achieving satisfactory performance based on the evaluation metrics.

## Conclusion

This project demonstrates a comprehensive approach to handling and analyzing real estate data, from initial preprocessing to building and evaluating a predictive model. The steps outlined provide a robust framework for similar data analysis tasks in the real estate domain.
