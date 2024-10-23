# Car Features Data Analysis

This repository contains an exploratory data analysis (EDA) of a dataset comprising various car features, including make, fuel type, engine specifications, and pricing. The analysis includes statistical tests, contingency tables, and key business insights aimed at optimizing inventory and pricing strategies for a car dealership.

## Project Overview

The main objective of this project is to:
- Explore car pricing across different makes and fuel types.
- Identify trends in luxury and non-luxury cars.
- Evaluate statistical relationships and probabilities related to car features.
- Provide actionable business insights based on the data.

### Key Insights:
- The **most expensive car** is a **Chevrolet** priced at **$40,450**, while the **cheapest car** is a **Ford** priced at **$8,246.50**.
- **Gas-powered cars** have a higher average price (**$24,979.23**) compared to **diesel cars** (**$20,199.42**), though the price difference is not statistically significant.
- **BMW** and **Audi** contribute heavily to the **luxury car segment**, accounting for **16%** and **12%** of the dataset, respectively.
- The probability of randomly selecting a **BMW** is **16%**, and selecting a **BMW** with an 8-cylinder engine is **40%**.

## Analysis Techniques

The following techniques were employed during the analysis:
1. **Descriptive Statistics**: To understand the distribution of car prices, makes, and fuel types.
2. **Contingency Tables**: To analyze the relationship between car makes and fuel types.
3. **T-Test**: To compare mean prices of gas and diesel cars and test for significant differences.
4. **Probability Calculations**: For assessing the likelihood of certain car features.

## Dataset

The dataset consists of **25 records** and **18 features**, including:
- **Make**: The manufacturer of the car (e.g., BMW, Audi).
- **Price**: The price of the car.
- **Fuel Type**: The type of fuel the car uses (Gas or Diesel).
- **Number of Cylinders**: Engine specification.
- **Aspiration**: Turbo or standard engine type.
- And more.

## Files

- **Car_Features_EDA.ipynb**: The Jupyter Notebook containing all the code and analysis.
- **car_features.csv**: The dataset used for analysis.
- **README.md**: This README file.

## Results Summary

### Descriptive Statistics:
- **Highest Priced Car**: Chevrolet ($40,450)
- **Lowest Priced Car**: Ford ($8,246.50)
- **Average Price by Fuel Type**:
  - Diesel: $20,199.42
  - Gas: $24,979.23

### Statistical Test:
- A **t-test** conducted between gas and diesel car prices resulted in a **p-value of 0.2728**, indicating no significant difference in mean prices at a 0.05 significance level.

### Contingency Table:
- Analyzed the distribution of makes across fuel types. **BMW** cars are exclusively diesel-powered, while **Audi** and **Mercedes** offer both gas and diesel variants.


