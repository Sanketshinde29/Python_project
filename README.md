🪔 Diwali Sales Analysis using Python
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a Diwali Sales dataset using Python.
The main goal of this analysis is to understand customer purchasing behavior, identify sales trends, and generate business insights from the dataset.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the dataset was cleaned, processed, analyzed, and visualized to uncover meaningful patterns.

🚀 Technologies & Libraries Used
🐍 Python
📊 Pandas
🔢 NumPy
📈 Matplotlib
🎨 Seaborn
📓 Jupyter Notebook
📂 Dataset Information

The dataset contains customer and sales-related information such as:

User ID
Customer Name
Product ID
Gender
Age Group
Marital Status
State
Occupation
Product Category
Orders
Amount

Dataset Shape:
(11251, 15)

🔍 Project Workflow
1️⃣ Importing Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

2️⃣ Data Loading
df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')

3️⃣ Data Cleaning
✔️ Removed Unnecessary Columns
df.drop(['Status', 'unnamed1'], axis=1, inplace=True)
✔️ Checked Null Values
pd.isnull(df).sum()
✔️ Removed Null Values
df.dropna(inplace=True)
✔️ Converted Data Types
df['Amount'] = df['Amount'].astype('int')


📊 Exploratory Data Analysis (EDA)
👩 Gender Analysis
Female customers contributed more to sales
Female purchasing power was higher than males
Visualization:
Gender Count Plot
Gender vs Amount Bar Chart

🎂 Age Group Analysis
Customers aged 26–35 years were the most active buyers
Female customers in this age group dominated purchases
Visualization:
Age Group Count Plot
Age Group vs Sales Amount

🌍 State-wise Sales Analysis
Top-performing states based on orders and sales amount:

Maharashtra
Uttar Pradesh
Karnataka
Visualization:
Top 10 States by Orders
Top 10 States by Sales Amount

💍 Marital Status Analysis
Married women showed higher purchasing behavior
Visualization:
Marital Status Count Plot
Marital Status vs Sales Amount

💼 Occupation Analysis
Top occupations contributing to sales:

IT Sector
Healthcare
Aviation
Visualization:
Occupation Count Plot
Occupation vs Sales Amount

🛍️ Product Category Analysis
Most sold product categories:

Food
Clothing
Electronics
Visualization:
Product Category Count Plot
Product Category vs Sales Amount
📈 Key Business Insights

✅ Female customers are the major buyers

✅ Customers aged 26–35 contribute most to sales

✅ Maharashtra, Uttar Pradesh, and Karnataka generate high revenue

✅ Married women have higher purchasing power

✅ IT, Healthcare, and Aviation professionals are major customers

✅ Food, Clothing, and Electronics are top-selling categories

🏁 Conclusion
This project helped in understanding how customer demographics influence purchasing behavior during festive sales.
By performing data cleaning, preprocessing, visualization, and analysis, meaningful business insights were extracted from the dataset.
The project also strengthened practical skills in:
Data Cleaning
Data Visualization
Exploratory Data Analysis
Business Insight Generation
Python for Data Analytics
