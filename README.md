Basic Statistics Analysis - Jupyter Notebook
This repository contains a Jupyter notebook that performs basic statistical analysis on a dataset, including information related to sales, product categories, brands, and pricing.

Features
Data Handling:
The dataset includes columns such as Brand, SKU, BU, Total Sales Value, Discount Rate, and Net Sales Value.
It performs operations like encoding categorical data using pd.get_dummies().
Statistical Operations:
Basic statistics such as averages and totals are calculated on key sales and pricing columns.
Dataset Overview
The dataset comprises sales data with the following fields:

Date: The date of sales.
Brand: Brand name of the products.
SKU: Stock Keeping Unit (product identifier).
BU: Business unit.
Avg Price: The average price of the items sold.
Total Sales Value: Total value of sales for each item.
Discount Rate (%): The discount applied to the items.
Net Sales Value: Total sales after discount.
Additional encoding is applied to categorical variables such as Day, SKU, BU, and Brand using one-hot encoding.

Key Operations
Data Encoding:

Categorical variables like Brand and BU are encoded using pd.get_dummies() to prepare the dataset for statistical modeling.
Statistical Insights:

Various columns like Total Sales Value, Discount Rate (%), and Net Sales Value are analyzed to draw insights from the dataset.
Requirements
Python 3.x
Jupyter Notebook
Pandas
