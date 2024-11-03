# Amazon-UK-Products-EDA-ML-Project

This repository contains a comprehensive analysis and machine learning project based on a dataset of Amazon products in the UK. The dataset includes information about product ratings, reviews, and pricing, allowing for in-depth exploration and predictive modeling.

## Dataset Overview

The dataset comprises 1,465 entries with the following features:

- `product_id`: Unique identifier for each product
- `product_name`: Name of the product
- `category`: Category of the product
- `discounted_price`: Discounted price of the product (float)
- `actual_price`: Actual price of the product (float)
- `discount_percentage`: Percentage discount applied to the product (float)
- `rating`: Product rating (float)
- `rating_count`: Number of ratings (int)
- `about_product`: Description of the product
- `user_id`: Unique identifier for the user who wrote the review
- `user_name`: Name of the user who wrote the review
- `review_id`: Unique identifier for the review
- `review_title`: Short review title
- `review_content`: Long review content
- `img_link`: Link to the product image
- `product_link`: Link to the product page

## Project Objectives

The main objectives of this project include:

- **Dataset Walkthrough**: Understanding the hierarchy and structure of the dataset.
- **Data Preprocessing**: Cleaning and transforming data types for analysis.
- **Exploratory Data Analysis (EDA)**: Analyzing trends, distributions, and relationships in the data.
- **Data Visualization**: Creating visual representations of key findings.
- **Machine Learning**: Building predictive models to forecast product ratings and performance.
- **Feature Engineering**: Enhancing model performance by creating new features.

## EDA Insights

During the exploratory data analysis, the following insights were uncovered:

- Identification of null values and their implications.
- Exploration of relationships between product features and ratings.
- Trend analysis of product categories and sales performance.

## Machine Learning Models

The following machine learning models were implemented:

1. **Linear Regression**: Used for predicting product ratings based on features.
2. **Random Forest**: A more complex model used to enhance prediction accuracy.

### Model Performance

- **Linear Regression**:
  - Mean Squared Error: `1.0195316760735116e-24`
  - R^2 Score: `1.0`
  
- **Random Forest**:
  - Mean Squared Error: `0.00010449488054607138`
  - R^2 Score: `0.9987296138475613`

## Visualizations

The following plots were generated to visualize model performance and feature importance:

- **Predicted vs. Actual Values**: Showcases the accuracy of the predictions.
- **Residuals Plot**: Analyzes the distribution of prediction errors.
- **Feature Importance Plot**: Identifies which features contribute most to the predictions in the Random Forest model.

## Getting Started

### Prerequisites

Make sure to have the following packages installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/samwanyua/Amazon-UK-Products-EDA-ML-Project.git
cd Amazon-UK-Products-EDA-ML-Project
pip install -r requirements.txt
```