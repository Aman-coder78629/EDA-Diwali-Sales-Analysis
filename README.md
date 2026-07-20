# EDA-Diwali-Sales-Analysis

# 🪔 EDA Diwali Sales Analysis using Python

# 📖 Project Overview

The **EDA Diwali Sales Analysis** project is a comprehensive **Exploratory Data Analysis (EDA)** project developed using **Python** and **Jupyter Notebook**. The primary objective of this project is to analyze customer purchasing behavior during the Diwali festival season and uncover valuable business insights that can help retailers improve their marketing strategies, inventory management, and customer targeting.

Diwali is one of the biggest shopping festivals in India, generating millions of transactions across various product categories. Understanding customer demographics, purchasing patterns, and product preferences enables businesses to maximize sales and improve customer satisfaction.

This project demonstrates the complete workflow of a real-world data analysis project, including data cleaning, preprocessing, visualization, statistical analysis, and business insight generation.

---

# 📌 Table of Contents

- Project Overview
- Business Problem
- Objectives
- Dataset Description
- Technologies Used
- Python Libraries
- Project Workflow
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Data Visualizations
- Business Questions Answered
- Key Insights
- Business Recommendations
- Results
- Folder Structure
- Installation Guide
- How to Run
- Future Enhancements
- Learning Outcomes
- Skills Demonstrated
- Author
- License

---

# 🏢 Business Problem

Retail companies generate a huge amount of customer transaction data during festive seasons. However, without proper analysis, businesses cannot fully understand customer buying behavior, spending habits, or product demand.

This project aims to answer important business questions such as:

- Which customers spend the most during Diwali?
- Which age groups contribute the highest sales?
- Which states generate maximum revenue?
- Which occupations purchase the most?
- Which product categories are most popular?
- Which gender spends more?
- Which marital status group purchases more products?

The answers to these questions help businesses make informed marketing and sales decisions.

---

# 🎯 Objectives

The primary objectives of this project are:

- Perform Exploratory Data Analysis (EDA) on Diwali sales data.
- Clean and preprocess customer transaction data.
- Handle missing values and duplicates.
- Analyze customer demographics.
- Understand purchasing behavior.
- Identify high-value customer segments.
- Explore product demand across categories.
- Generate meaningful business insights.
- Create professional visualizations for better interpretation.

---

# 📂 Dataset Description

The dataset contains customer purchase information collected during the Diwali shopping season.

### Dataset Features

| Feature | Description |
|----------|-------------|
| User_ID | Unique customer ID |
| Cust_name | Customer name |
| Product_ID | Product identifier |
| Gender | Customer gender |
| Age Group | Customer age category |
| Age | Customer age |
| Marital_Status | Married or Unmarried |
| State | Customer state |
| Zone | Region |
| Occupation | Customer occupation |
| Product_Category | Product category |
| Orders | Number of orders |
| Amount | Purchase amount |

The dataset provides rich information for analyzing customer behavior and sales trends.

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📚 Python Libraries

```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🚀 Project Workflow

The project follows a structured data analytics workflow.

## Step 1 – Import Libraries

Import all necessary Python libraries for data manipulation and visualization.

---

## Step 2 – Load Dataset

Load the Diwali sales dataset into a Pandas DataFrame.

```python
df = pd.read_csv("Diwali Sales Data.csv", encoding='unicode_escape')
```

---

## Step 3 – Explore Dataset

The dataset is explored using:

- Shape
- Data types
- Summary statistics
- Column information
- Missing values

Functions used:

```python
df.head()
df.info()
df.describe()
```

---

## Step 4 – Data Cleaning

Data cleaning includes:

- Removing unnecessary columns
- Handling missing values
- Removing duplicate records
- Correcting data types
- Verifying data consistency

This ensures the dataset is suitable for analysis.

---

## Step 5 – Data Preprocessing

Several preprocessing operations are performed, including:

- Converting data types
- Handling null values
- Renaming columns
- Preparing categorical features for analysis

---

# 📊 Exploratory Data Analysis (EDA)

The notebook performs detailed analysis on customer purchasing behavior.

---

## 👨 Gender Analysis

The project compares purchases made by male and female customers.

Visualization:

- Count Plot
- Bar Chart

Business Insight:

Understand which gender contributes more to total sales.

---

## 🎂 Age Group Analysis

Customer purchases are analyzed across different age groups.

Visualization:

- Count Plot
- Sales Distribution

Purpose:

Identify the most valuable customer age segment.

---

## 💍 Marital Status Analysis

Purchasing behavior is compared between married and unmarried customers.

Visualization:

- Count Plot
- Sales Comparison

Business Benefit:

Target promotions based on family status.

---

## 🌍 State-wise Sales Analysis

The project identifies states generating maximum revenue.

Visualization:

- Top 10 States Bar Chart

Business Insight:

Recognize high-performing markets.

---

## 🧑‍💼 Occupation Analysis

Customer occupations are analyzed to determine spending patterns.

Visualization:

- Occupation-wise Sales Bar Chart

Purpose:

Identify customer professions with higher purchasing power.

---

## 🛍 Product Category Analysis

Sales across different product categories are explored.

Visualization:

- Product Category Bar Chart

Examples:

- Clothing
- Electronics
- Food
- Footwear
- Home Decor
- Beauty Products

Business Insight:

Understand which products perform best during Diwali.

---

## 📦 Product Analysis

The notebook identifies the most frequently purchased products.

Visualization:

- Top Products Bar Chart

Useful for:

- Inventory planning
- Product recommendation
- Marketing strategy

---

## 💰 Revenue Analysis

The total purchase amount is analyzed across multiple customer segments.

Visualizations include:

- Sales by Gender
- Sales by Age
- Sales by State
- Sales by Occupation
- Sales by Product Category

---

# 📈 Visualizations Included

The project generates multiple professional charts.

- Count Plot
- Bar Chart
- Histogram
- Pie Chart
- Line Chart (where applicable)
- Sales Comparison Charts
- Product Analysis Charts


# 📌 Results

The project successfully demonstrates:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Customer Segmentation
- Sales Analysis
- Product Analysis
- Data Visualization
- Business Intelligence
- Insight Generation

# 📸 Expected Outputs

The notebook produces:

- Gender Analysis Charts
- Age Group Distribution
- Marital Status Analysis
- State-wise Sales Analysis
- Occupation Analysis
- Product Category Analysis
- Product Purchase Trends
- Revenue Distribution Charts
- Customer Demographic Insights

---

# 🚀 Future Enhancements

Possible improvements include:

- Interactive Streamlit Dashboard
- Power BI Dashboard
- Tableau Dashboard
- Customer Segmentation using Machine Learning
- Sales Forecasting
- Customer Lifetime Value Prediction
- Recommendation System
- Interactive Plotly Visualizations
- Real-time Sales Dashboard

---

# 🎓 Learning Outcomes

This project provides hands-on experience in:

- Python Programming
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Analytics
- Customer Behavior Analysis
- Retail Sales Analysis
- Statistical Thinking
- Data Storytelling

---

# 💼 Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Customer Analytics
- Retail Analytics
- Data Visualization
- Business Intelligence

