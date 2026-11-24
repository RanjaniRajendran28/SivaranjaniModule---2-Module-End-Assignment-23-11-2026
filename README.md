# SivaranjaniModule---2-Module-End-Assignment-23-11-2026

🛒 Online Retail Data Analysis Project
📌 Project Overview

This project focuses on analyzing an Online Retail dataset using Python to understand sales trends, customer purchasing behavior, product performance, and business insights.

The project involves data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), statistical analysis, data visualization, and business insight generation.

The main objective is to transform raw retail transaction data into meaningful insights that help businesses make data-driven decisions.

🎯 Project Objectives
Clean and preprocess real-world retail data.
Handle missing values, duplicates, and invalid records.
Perform Exploratory Data Analysis (EDA).
Create new features using feature engineering.
Analyze customer purchasing behavior.
Identify top-performing countries and products.
Perform statistical analysis.
Visualize sales trends using Matplotlib and Seaborn.
Generate actionable business insights.
Maintain project version control using Git and GitHub.
📂 Dataset Information

Dataset Name: Online Retail Dataset

Source: UCI Machine Learning Repository

Dataset Link: https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains transactions from a UK-based online retail store.

Dataset Features
Column	Description
InvoiceNo	Unique invoice number
StockCode	Product identification code
Description	Product description
Quantity	Number of products purchased
InvoiceDate	Date and time of transaction
UnitPrice	Price per unit
CustomerID	Unique customer identification
Country	Customer's country
🛠️ Technologies Used
Python – Programming language
NumPy – Numerical computations
Pandas – Data cleaning and manipulation
Matplotlib – Data visualization
Seaborn – Statistical data visualization
Jupyter Notebook – Interactive development environment
VS Code – Code editor
Git & GitHub – Version control and project hosting
📋 Project Tasks
Task 1 – Data Import & Setup
Imported the dataset using Pandas.
Explored dataset structure using head(), tail(), shape, and columns.
Converted InvoiceDate into datetime format.
Task 2 – Data Cleaning
Handled missing CustomerID values.
Removed duplicate records.
Removed negative and zero quantities.
Removed invalid and zero unit prices.
Task 3 – Feature Engineering
Created TotalPrice using Quantity × UnitPrice.
Extracted Year, Month, Day, and Hour.
Created Customer Segment categories.
Created Order Size categories.
Created Day Type categories.
Task 4 – Data Exploration
Analyzed dataset using describe().
Explored categories using value_counts() and unique().
Performed groupby analysis by country, month, and product.
Task 5 – Data Wrangling
Aggregated data using groupby().
Identified top customers and countries.
Sorted product sales.
Restructured data using pivot_table() and reset_index().
Task 6 – Statistical Analysis

Calculated the following statistical measures:

Mean
Median
Mode
Standard Deviation
Variance
Percentiles

Analyzed Quantity, UnitPrice, and TotalPrice.

Task 7 – Data Visualization using Matplotlib

Created the following visualizations:

Monthly Sales Line Chart
Daily Sales Line Chart
Top 10 Countries Bar Chart
Top 10 Products Bar Chart
Quantity Histogram
UnitPrice Histogram
TotalPrice Box Plot
Quantity Box Plot
Task 8 – Data Visualization using Seaborn

Created:

Count Plot
Violin Plot
Correlation Heatmap
Pair Plot
Task 9 – Business Insights

Analyzed:

Top-performing country
Best sales month
Peak sales time
Customer purchasing behavior
High-value customers
Top-performing products
Task 10 – GitHub Project Implementation
Created project folder structure.
Organized project files.
Created README.md and requirements.txt.
Initialized Git repository.
Committed project changes.
Uploaded the project to GitHub.
📁 Project Folder Structure
text
Online-Retail-Data-Analysis/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebooks/
│   └── Online_Retail_Analysis.ipynb
│
├── scripts/
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   └── visualization.py
│
├── README.md
├── requirements.txt
└── .gitignore

⚙️ Installation and Setup
1. Clone the repository
bash
git clone <your-github-repository-url>

2. Navigate to the project folder
bash
cd Online-Retail-Data-Analysis

3. Install required libraries
bash
pip install -r requirements.txt

4. Download the dataset

Download the Online Retail dataset from:

https://archive.ics.uci.edu/dataset/352/online+retail

Place the downloaded Excel file inside the data/ folder.

5. Run the Jupyter Notebook
bash
jupyter notebook


Open Online_Retail_Analysis.ipynb and execute the cells sequentially.

📦 Requirements

The project requires the following Python libraries:

text
pandas
numpy
matplotlib
seaborn
openpyxl
jupyter

📊 Expected Business Insights

This project helps identify:

The country generating the highest revenue.
The month with the highest sales.
Peak shopping hours.
High-value customers based on spending.
Best-performing products based on revenue.
Customer purchasing patterns.
Sales distribution and trends.
💡 Business Benefits
Improve sales forecasting.
Identify profitable markets.
Understand customer purchasing behavior.
Improve inventory management.
Identify valuable customers.
Develop effective marketing strategies.
Support data-driven business decisions.
🏁 Conclusion

The Online Retail Data Analysis project demonstrates how Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn can be used to analyze real-world retail transaction data.

Through data cleaning, feature engineering, exploratory data analysis, statistical analysis, and visualization, the project transforms raw transaction records into meaningful business insights.

The findings can help businesses understand sales performance, customer behavior, and product demand, ultimately supporting better business decisions.



This project is intended for educational and learning purposes.

Dataset usage is subject to the UCI repository's dataset terms.
