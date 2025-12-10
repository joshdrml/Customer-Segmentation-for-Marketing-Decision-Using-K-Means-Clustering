# Customer-Segmentation-for-Marketing-Decision-Using-K-Means-Clustering
A Python-based project that segments Nigerian retail and e-commerce customers using unsupervised machine learning. Analyze customer behavior, discover actionable insights, and enable targeted marketing strategies. Includes data preprocessing, clustering, visualizations, and detailed analysis.

# Nigerian Retail & E-Commerce Customer Segmentation

This repository contains a project for **customer segmentation** based on Nigerian retail and e-commerce customer data. The goal is to analyze customer behavior, identify meaningful segments, and provide insights to improve marketing, product recommendations, and customer engagement strategies.

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Methodology](#methodology)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  

## Project Overview

Customer segmentation is an essential task in data analytics and marketing. This project leverages retail and e-commerce customer data to:

- Identify distinct customer groups based on purchasing behavior.  
- Understand patterns in demographics, spending habits, and product preferences.  
- Enable targeted marketing strategies and improve customer satisfaction.  

The project uses Python, pandas, and other data science tools to clean, analyze, and visualize the data.

## Dataset

The dataset used is the **Nigerian Retail & E-Commerce Customer Segmentation Data**. It contains features related to:

- Customer demographics (age, gender, location)  
- Purchase history (transaction frequency, amount spent)  
- Customer behavior metrics  

> **Note:** The `segment` column has been removed to focus on unsupervised segmentation.  

Dataset source: [HuggingFace Dataset](https://huggingface.co/datasets/electricsheepafrica/nigerian_retail_and_ecommerce_customer_segmentation_data)


# Nigerian Retail & E-Commerce Customer Segmentation

This repository contains a Python-based project for customer segmentation using Nigerian retail and e-commerce data. The goal is to analyze customer behavior, identify meaningful segments, and generate actionable insights for marketing and business strategy.

## Required Python Packages

- pandas  
- numpy  
- matplotlib / seaborn  
- scikit-learn  
- jupyter / jupyterlab  

## Usage

1. Load the dataset:
   
```python
import pandas as pd

df = pd.read_parquet("nigerian_retail_and_ecommerce_customer_segmentation_data.parquet")
df.head()

```
2. Perform data cleaning, feature selection, and preprocessing.  
3. Apply clustering algorithms (e.g., K-Means) to segment customers.  
4. Analyze and visualize results using charts and graphs.  

## Methodology

- **Data Cleaning:** Handling missing values, duplicates, and irrelevant columns.  
- **Exploratory Data Analysis (EDA):** Summary statistics, correlations, and visualizations.  
- **Feature Engineering:** Creating meaningful features to improve clustering.  
- **Clustering:** Using K-Means clustering to segment customers into distinct groups.  
- **Evaluation & Insights:** Analyzing clusters to understand customer behavior and characteristics.  

## Results

The project identifies several customer segments with actionable insights:

- **High-value customers:** Frequent, high-spending.  
- **Medium-value customers:** Moderate engagement.  
- **Low-value / customers at risk:** Infrequent purchases.  

Visualizations such as bar charts, scatter plots, and heatmaps are included to interpret these segments.  

## Contributing

Contributions are welcome! You can:

- Add new visualizations  
- Explore alternative clustering techniques  
- Improve feature engineering  
- Extend analysis to predictive modeling  

