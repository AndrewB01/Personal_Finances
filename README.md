
## Personal Expense Tracker and Analysis Project ##

## Overview
Since 2023, I have been tracking all my expenses by item in an Excel file. This project aims to clean, analyze, and visualize this data to gain insights into my spending habits, identify cost-saving opportunities, and showcase my skills in Python for data cleaning, analysis, and visualization. The cleaned data will also be used to create interactive reports in Power BI.

This project demonstrates my ability to:
- Clean and preprocess raw data using Python.
- Perform exploratory data analysis (EDA) to uncover trends and patterns.
- Visualize data to communicate insights effectively.
- Integrate Python with Power BI for reporting and dashboard creation.

## Project Goals
1. **Data Cleaning and Preprocessing**:
   - Clean the raw expense data to handle missing values, duplicates, and inconsistencies.
   - Standardize the format of the data for analysis.

2. **Data Analysis**:
   - Analyze spending patterns by category (e.g., food shopping, entertainment, dog food, restaurants).
   - Identify trends in expenses over time (monthly, weekly, yearly).
   - Compare costs across stores to find the best value for groceries and restaurants.
   - Evaluate spending relative to monthly income.

3. **Data Visualization**:
   - Create visualizations to show expense distribution, trends, and comparisons.
   - Generate insights into where and how to optimize spending.

4. **Power BI Integration**:
   - Export cleaned data to Power BI for interactive reporting.
   - Build dashboards to showcase expense analysis and insights.

## Data Description
The dataset includes the following information for each purchase:
- **Store**: The name of the store where the purchase was made.
- **Item**: The name of the item purchased.
- **Quantity**: The number of units purchased.
- **Cost Per Unit**: The price of one unit of the item.
- **Total Cost**: The total cost of the purchase (Quantity × Cost Per Unit).
- **Category**: The category of the expense (e.g., food shopping, entertainment, dog food, restaurants).
- **Date**: The date of the purchase.

## Tools and Technologies
- **Python**: For data cleaning, analysis, and visualization.
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly.
- **Power BI**: For creating interactive dashboards and reports.
- **Excel**: For initial data entry and storage.

## Project Structure
```
project-folder/
│
├── data/
│   ├── raw/                  # Contains the original Excel file with raw data.
│   └── compile_raw_data/            # Contains cleaned and processed data files.
│
├── notebooks/
│   ├── data_cleaning.ipynb   # Jupyter notebook for cleaning and preprocessing data.
│   ├── data_analysis.ipynb   # Jupyter notebook for exploratory data analysis.
│   └── data_viz.ipynb        # Jupyter notebook for creating visualizations.
│
├── scripts/
│   ├── clean_data.py         # Python script for cleaning data.
│   ├── analyze_data.py       # Python script for analyzing data.
│   └── visualize_data.py     # Python script for generating visualizations.
│
├── reports/
│   ├── power_bi/             # Contains Power BI files and dashboards.
│   └── visualizations/       # Contains exported visualizations (e.g., PNG, PDF).
│
├── README.md                 # This file.
└── requirements.txt          # List of Python dependencies.
```

## Key Insights
- **Expense Distribution**: Breakdown of expenses by category (e.g., food shopping, entertainment).
- **Trends Over Time**: Monthly, weekly, and yearly spending patterns.
- **Cost Comparisons**: Identify stores with the best value for groceries and restaurants.
- **Budget Control**: Analyze spending relative to monthly income and identify areas for optimization.

## How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/AndrewB01/Personal_Finances.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data cleaning, analysis, and visualization scripts or notebooks.
4. Open the Power BI files in the `reports/power_bi/` folder to explore the interactive dashboards.
