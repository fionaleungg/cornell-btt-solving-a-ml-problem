# cornell-btt-solving-a-ml-problem

## Airbnb Price Prediction – Fall AI Studio Project
### Project Overview
This project explores the use of machine learning to predict Airbnb listing prices based on various listing features from New York City. The dataset includes attributes such as number of bedrooms, room type, location, and other listing metadata. Our goal is to build an effective model that helps understand what features most influence rental price.

### Objectives and Goals
Define a machine learning problem using real-world Airbnb data.

Explore the dataset to understand important features and trends.

Build and evaluate predictive models for Airbnb listing prices.

Use insights to potentially guide hosts or renters on price expectations.

### Methodology
Data Selection: We used the airbnbListingsData.csv dataset.

Problem Definition: A regression problem was defined to predict the price of listings.

Exploratory Data Analysis:

Checked for missing values and data types.

Visualized distributions and relationships between numerical features.

Used correlation heatmaps to identify important predictors of price.

Data Preprocessing:

Selected relevant numeric features.

Handled outliers and normalized values.

Split the data into training and test sets.

Model Training:

Trained a linear regression model as a baseline.

Used Random Forest Regressor to improve performance.

Model Evaluation:

Compared models using R² scores and RMSE.

Visualized predictions vs actual values.

### Results and Key Findings
The Random Forest Regressor outperformed the baseline model with a higher R² score and lower RMSE.

Features most correlated with price include number_of_reviews, availability_365, and minimum_nights.

Despite noise in price data, models were able to capture general pricing trends.

### Visualizations
Correlation heatmaps for numeric variables.

Scatter plots showing the relationship between top features and price.

Model performance visualizations (e.g. residual plots, prediction vs actual).

### Potential Next Steps
Tune hyperparameters of Random Forest for better performance.

Incorporate categorical features using one-hot encoding.

Use geographic information (latitude and longitude) to cluster listings.

Evaluate models using cross-validation for robustness.

### Individual Contributions
This project was completed individually. All steps—from problem definition, exploratory analysis, modeling, and evaluation—were conducted by me, including code development and interpretation of results.

