# Week_1
Week1 Task: Solar Power Prediction Analysis and Model Development  This week, the focus was on exploring and analyzing the dataset solarpowergeneration.csv to understand its structure and key features.
Solar Power Prediction using Linear Regression

## Overview

The Solar Power Prediction project leverages a dataset named solarpowergeneration.csv to predict solar power output using a Linear Regression model. The project is designed to help analyze and preprocess data, explore relationships between variables, and build a predictive model to forecast solar power generation.

Features

## The project includes the following functionalities:

-- Dataset Loading

Loads the dataset (solarpowergeneration.csv) using Pandas.

Displays key insights such as the first and last few rows of the dataset.

-- Exploratory Data Analysis (EDA)

Shows the structure and size of the dataset.

Provides statistical summaries and dataset information.

Checks for missing and duplicate values.

-- Data Visualization

Plots the distribution of key variables such as generated_power_kw.

Visualizes relationships between features using pair plots and correlation heatmaps.

-- Data Cleaning and Preprocessing

Handles missing values using imputation or removal techniques.

Scales and normalizes numerical features for better model performance.

-- Linear Regression Model

Builds a predictive model to estimate solar power output.

Evaluates the model's performance using metrics such as Mean Squared Error (MSE) and R-squared.

## The following Python libraries are required:

pandas: For data manipulation and analysis.

numpy: For numerical computations.

matplotlib: For creating visualizations.

seaborn: For statistical data visualization.



## Install the dependencies using:

pip install pandas numpy matplotlib seaborn scikit-learn


## How to Use

Ensure the dataset (solarpowergeneration.csv) is in the same directory as the project files.

Run the Jupyter Notebook or Python script provided.

Follow the step-by-step instructions to load the dataset, analyze the data, and build the regression model.

Customize the analysis or model parameters as needed.


## File Structure

solarpowergeneration.csv: The dataset file containing historical solar power data.

dataset_analysis.ipynb: Jupyter Notebook for data analysis and visualization.

README.md: This file, providing an overview of the project.


## Results

The Linear Regression model predicts solar power output based on features such as temperature, humidity, and time.

Key insights and model performance metrics are displayed at the end of the analysis.



# WEEK 2: Exploratory Data Analysis (EDA)

## Overview
In this week, we perform an in-depth **Exploratory Data Analysis (EDA)** to better understand the dataset and its features. The key focus areas include:

- Histogram Analysis of Features
- Bivariate Analysis using Scatter Plots and Correlation Heatmap
- Outlier Detection using Boxplots

## 1. Histogram Analysis
To understand the distribution of each numerical feature, histograms are plotted for all numerical columns. Additionally, for better visualization, histograms are split into multiple sections.

## 2. Bivariate Analysis - Scatter Plots and Correlation Heatmap
Scatter plots are used to visualize relationships between features and the target variable (**Generated Power (kW)**). A correlation heatmap is also generated to analyze feature dependencies.

## 3. Outlier Detection - Boxplots
Boxplots help in detecting outliers for each numerical column, which can significantly impact model performance and accuracy.

## Summary
By performing **histogram analysis, scatter plots, correlation heatmaps, and boxplots**, we gain a deeper insight into the dataset, detect potential issues like outliers, and understand feature relationships. This analysis helps in better data preprocessing and model building in the next phase.





