# Zomato Dataset EDA

This repository contains an exploratory data analysis (EDA) of the Zomato dataset, focusing on various aspects of restaurants across multiple countries. The analysis includes data preprocessing, visualization, and merging of additional country information.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis Steps](#analysis-steps)
- [Visualizations](#visualizations)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The primary goal of this project is to analyze the Zomato dataset to extract insights related to restaurants, their locations, and customer ratings across various countries. This analysis provides valuable information about the global restaurant industry, customer preferences, and trends.

## Dataset

The dataset used in this analysis includes the following files:
- `zomato.csv`: Contains detailed information about restaurants.
- `Country-code.xlsx`: Provides a mapping between country codes and country names.

## Analysis Steps

The analysis performed in this project covers the following steps:

1. **Data Loading and Inspection**
   - Load the Zomato dataset and inspect the columns and data types.
   - Check for missing values and handle them appropriately.
   
2. **Data Cleaning**
   - Fix encoding issues.
   - Handle missing values, focusing on critical columns like `Cuisines`.
   
3. **Merging Datasets**
   - Merge the Zomato dataset with the country codes dataset to add country names.
   
4. **Exploratory Data Analysis**
   - Explore numerical variables like `Average Cost for two`, `Price range`, and `Aggregate rating`.
   - Explore categorical variables such as `City`, `Cuisines`, and `Country`.
   - Analyze relationships between features, including geographical distribution and rating patterns.

5. **Visualizations**
   - Visualize the distribution of restaurants by country.
   - Analyze the top cuisines offered across different countries.
   - Create pie charts for top countries with the most restaurants.

## Visualizations

Some of the key visualizations generated in this analysis include:
- **Pie Chart:** Distribution of restaurants by country.
- **Bar Plots:** Average cost distribution by country and rating color distribution.
- **Heatmap:** Display of missing values in the dataset.

## Results
The results of this analysis highlight:

- The dominance of India in the Zomato dataset in terms of the number of restaurants.
- The popularity of various cuisines across different countries.
- Insights into the price range and customer ratings distribution globally.
## Requirements

To run the analysis, ensure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn
