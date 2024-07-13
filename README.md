# Sales-Prediction
### Sales Prediction Analysis

This notebook provides an analysis for predicting sales based on advertising data using various data science and machine learning techniques. Below is a summary of the steps and processes undertaken in the notebook:

#### Importing Libraries
The necessary libraries for data manipulation, visualization, and machine learning are imported:
- `pandas` and `numpy` for data manipulation
- `seaborn` and `matplotlib` for data visualization
- `sklearn` for machine learning models and evaluation

#### Data Loading and Initial Exploration
The advertising dataset is loaded from a CSV file, followed by an initial exploration:
- Displaying the dataset and checking its structure
- Verifying data types and checking for missing values

#### Data Visualization
Several visualizations are created to understand the data better:
- Pairplot to visualize relationships between advertising channels and sales
- Heatmap to show the correlation between different features

#### Feature Selection
The features (TV, Radio, Newspaper) and target (Sales) variables are selected for model training:
- Separating features (`X`) and target (`y`) variables

#### Model Training
- Splitting the data into training and testing sets
- Training a Linear Regression model on the training data
- Making predictions on the testing data

#### Model Evaluation
The model's performance is evaluated using:
- Mean Squared Error (MSE)
- R-squared value (R²)

#### Visualization of Predicted vs. Actual Sales
A scatter plot is created to visualize the relationship between actual and predicted sales.

#### Using the Model for Predictions
The model is used to predict sales based on new advertising data inputs.

#### Conclusion
This notebook provides a detailed approach to data exploration, visualization, preprocessing, and model training to predict sales based on advertising data. The steps outlined ensure a thorough and methodical approach to handling and analyzing the dataset.

This analysis and the steps involved can serve as a valuable reference for similar machine learning projects, highlighting the importance of data preparation and proper evaluation metrics.

You can view and run this analysis using the provided Jupyter Notebook file in this repository.
