# sales-analysis
A full analysis of sales data what is present is cleaning data,analyzing the data ,visualizing and giving notes 
# Sales Data Analysis Project

## Overview
This project performs a complete exploratory data analysis (EDA) on a retail sales dataset. The goal is to clean raw data, analyze customer behavior, and extract meaningful business insights using Python.

The workflow includes data cleaning, preprocessing, visualization, and insight generation.

---

## Objectives
- Clean and prepare raw sales data for analysis
- Handle missing values, duplicates, and inconsistent formatting
- Explore customer behavior and sales patterns
- Analyze relationships between variables
- Generate business insights through visualizations

---

## Dataset Description
The dataset contains retail sales transactions with the following key features:
- Order ID
- Order Date
- City
- Product Category
- Payment Method
- Customer Age
- Order Total
- Customer Rating

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning Steps
- Removed duplicate records
- Handled missing values using median imputation
- Converted data types (dates and IDs)
- Standardized text values (city, payment method, product category)
- Removed invalid values (negative or zero values)
- Created age groups for better analysis

---

## Exploratory Data Analysis (EDA)

### 1. Correlation Analysis
Identified relationships between numerical variables using a correlation heatmap.

### 2. Customer Age vs Spending
Analyzed whether customer age affects order total using scatter plots and regression lines.

### 3. Distribution Analysis
Studied distributions of:
- Customer age
- Order total values

### 4. Payment Behavior
Analyzed payment method distribution and its variation across cities.

### 5. Revenue Analysis
- Revenue by product category
- Revenue by city

### 6. Payment Preferences
Visualized overall payment method share.

---

## Key Insights
- There is a weak positive correlation between customer age and spending.
- Cash is the most commonly used payment method.
- Revenue varies significantly across product categories.
- Certain cities generate higher total revenue than others.
- Customer age is mostly concentrated in young to middle-aged groups.

---

## Visualizations
All visualizations are stored in the `figures/` folder, including:
- Correlation matrix
- Distribution plots
- Boxplots with outliers
- Heatmaps
- Revenue analysis charts

---

# Hypothesis:
# Higher cash payment rates may be influenced by factors such as customer payment preferences,
# limited availability of digital payment options, or local purchasing habits.

# Hypothesis:
# Electronics generate the highest revenue because electronic products typically have
# higher prices than products in other categories, resulting in greater total sales revenue.

---

## Project Structure
```
sales-analysis/
│
├── analysis.py
├── finalproject.csv
├── README.md
│
├── figures/
│   ├── correlation_matrix.png
│   ├── age_vs_order_total.png
│   ├── order_total_boxplot.png
│   ├── customer_age_distribution.png
│   ├── order_total_distribution.png
│   ├── payment_method_distribution.png
│   ├── city_distribution.png
│   ├── payment_method_by_city.png
│   ├── revenue_by_category.png
│   ├── revenue_by_city.png
│   └── payment_method_share.png
```

---

## Conclusion
This project demonstrates how raw sales data can be transformed into meaningful insights through proper cleaning, analysis, and visualization. It provides a foundation for data-driven decision making in retail businesses.

---

## Future Improvements
- Add advanced statistical testing
- Build interactive dashboards (Power BI or Tableau)
- Work with larger datasets for deeper insights
