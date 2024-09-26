# Dynamic Pricing Strategy

## Project Overview
This project demonstrates the development of a dynamic pricing strategy for a ride-hailing service. The goal is to implement an algorithm that adjusts ride prices based on various factors such as demand, supply, and ride duration. The project includes both exploratory data analysis and the implementation of a predictive model using machine learning.

## Key Features
#### Exploratory Data Analysis (EDA):

Visualization of relationships between ride duration, historical ride cost, and vehicle types.

Correlation matrix to identify significant relationships between key features such as number of riders, number of drivers, and ride cost.

#### Dynamic Pricing Model:

The implementation of a dynamic pricing algorithm that adjusts the cost of rides based on demand and supply.

Multipliers are calculated based on percentiles of rider and driver availability, and prices are adjusted accordingly.

A comparison is made between historical and adjusted ride costs, identifying profitable and loss-making rides.

#### Visualization:

Multiple visualizations using Plotly, including scatter plots and heatmaps to visualize trends, distributions, and correlations.

Donut charts to display the distribution of profitable and loss rides under the dynamic pricing model.

#### Predictive Modeling:

A random forest regression model is trained to predict ride prices based on inputs such as the number of riders, number of drivers, vehicle type, and expected ride duration.

Model evaluation using actual vs. predicted values to assess performance.

#### User Input Price Prediction:

A functionality that allows users to input ride details such as vehicle type, number of riders, number of drivers, and ride duration to predict the dynamic ride cost.

## Dataset

The dataset used in this project contains information on ride demand, driver availability, vehicle types, and historical ride costs. The data has been cleaned and preprocessed to handle missing values and outliers, ensuring reliable analysis and predictions.

## Tools and Libraries

**Pandas:** Used for data manipulation and analysis, particularly for handling datasets, cleaning, and preprocessing.

**Numpy:** For numerical operations, including the calculation of demand and supply multipliers and handling missing values.

**Plotly:** Utilized for creating interactive visualizations such as scatter plots, box plots, heatmaps, and donut charts to display data insights and model results.

**Scikit-learn:** Used for machine learning tasks, including data preprocessing (train-test split, scaling), and for training the Random Forest Regression model to predict adjusted ride costs.

## Predictive Model
The Random Forest Regression model was used to predict the adjusted ride cost based on historical ride data. The model was trained and tested on key features, and the performance was visualized through an "Actual vs Predicted" plot.

## Conclusion
The project successfully implements a dynamic pricing strategy that optimizes ride prices based on demand and supply, allowing for profitability while maintaining competitive pricing. The visualizations and predictive model provide insightful ways to analyze and forecast ride costs under different conditions.
