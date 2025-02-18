Mental Health Data Analysis Project
Overview
This project analyzes mental health prevalence data across different countries and conditions, using Python to perform statistical analysis and create visualizations. The analysis focuses on various mental health disorders including schizophrenia, depression, anxiety, bipolar disorder, and eating disorders.
Dataset Description
The project uses multiple datasets:

Mental illness prevalence data
Disease burden data (DALYs)
Adult population coverage data
Anxiety disorders treatment gap data
Depressive symptoms across US population
Country-wise primary data on mental illness prevalence

Dependencies
pythonCopynumpy
pandas
matplotlib
seaborn
scikit-learn
plotly
Project Structure
1. Data Import and Initial Setup

Imports necessary libraries
Loads multiple CSV files containing mental health data
Sets up plotting configurations

2. Data Cleaning and Preprocessing

Checks for missing values using custom describe() function
Renames columns for better readability
Handles data type conversions
Processes special characters and invalid entries

3. Exploratory Data Analysis (EDA)
Visualization Highlights:

Bar charts comparing mental health conditions across regions
Dynamic subplots showing relationship between bipolar disorder and major depression
Line plots of depressive symptoms across US population
Global burden of disease study visualization
Correlation heatmap between different mental health conditions
Scatter plots examining relationships between disorders
Box plots for distribution analysis

4. Statistical Analysis

Correlation analysis between different mental health disorders
Normalization of features using MinMaxScaler
Linear regression modeling
Cross-validation using K-Fold

5. Predictive Modeling

Implements simple linear regression
Features engineering (squared terms and interaction terms)
Model evaluation using various metrics:

Mean Absolute Error
Mean Squared Error
Root Mean Squared Error
R² Score



6. Results Visualization

Scatter plots comparing predicted vs actual values for:

Bipolar disorder
Schizophrenia
Anxiety disorders
Depressive disorders



Key Findings

Strong correlations exist between certain mental health conditions
The model achieved an R² score of approximately 0.68 after feature engineering
Predictive accuracy varies across different mental health conditions
Geographic variations in mental health prevalence are significant

Model Performance

Initial Linear Regression R² Score: 0.63
Improved R² Score after feature engineering: 0.68
Cross-validation scores show consistent performance across folds

Usage

Clone the repository
Install required dependencies:
bashCopypip install -r requirements.txt

Run the Jupyter notebook:
bashCopyjupyter notebook


Future Improvements

Include more recent data
Implement more advanced machine learning models
Add interactive dashboards
Incorporate demographic factors
Analyze treatment effectiveness data

Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
License
